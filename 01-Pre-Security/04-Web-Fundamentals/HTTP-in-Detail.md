# HTTP in Detail

**HTTP (Hypertext Transfer Protocol)** is used for communication between clients, such as browsers, and web servers. The browser sends a request and the server returns a response containing data such as page content.

## HTTP and HTTPS
HTTP by itself does not encrypt traffic. Depending on the network and circumstances, unencrypted requests and responses may be visible to parties able to observe them.

**HTTPS** is HTTP protected by **TLS (Transport Layer Security)**, which encrypts the connection and helps protect data in transit. A browser's lock or connection indicator generally signals a secure connection, but it does not guarantee that a website itself is trustworthy.

Analogy:
- **HTTP:** like sending a postcard that may be read in transit.
- **HTTPS:** like sending a message in a locked container.

[Back to Web Fundamentals](README.md)
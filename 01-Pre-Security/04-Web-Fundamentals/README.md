# Web Fundamentals

## 1. DNS in Detail
**DNS (Domain Name System)** helps people use domain names instead of memorizing IP addresses. DNS lookups can return records that help clients locate services.

### Domain hierarchy
- **TLD (Top-Level Domain):** the label at the end of a domain name, such as .com, .org, .edu, or .gov.
- **Subdomain:** an additional label before the main domain to separate services or areas of a website.

For **admin.tryhackme.com**:
- **admin** — subdomain
- **tryhackme** — domain label
- **.com** — top-level domain

## 2. HTTP in Detail
**HTTP (Hypertext Transfer Protocol)** is used for communication between clients, such as browsers, and web servers. The browser sends a request and the server returns a response containing data such as page content.

### HTTP and HTTPS
HTTP by itself does not encrypt traffic. Depending on the network and circumstances, unencrypted requests and responses may be visible to parties able to observe them.

**HTTPS** is HTTP protected by **TLS (Transport Layer Security)**, which encrypts the connection and helps protect data in transit. A browser's lock or connection indicator generally signals a secure connection, but it does not guarantee that a website itself is trustworthy.

Analogy:
- **HTTP:** like sending a postcard that may be read in transit.
- **HTTPS:** like sending a message in a locked container.

## 3. How Websites Work
When you visit a website, your browser sends a request to a web server. The server responds with data the browser uses to display the page.

### Two major components
1. **Front end (client side):** the parts users see and interact with.
2. **Back end (server side):** server-side logic and systems that process requests, access data, and provide responses.

### Core front-end technologies
- **HTML (HyperText Markup Language):** defines page structure and content, such as headings, text, images, and links.
- **CSS (Cascading Style Sheets):** controls presentation, including colors, fonts, spacing, and layout.
- **JavaScript:** adds behavior and interactivity, such as buttons, menus, and dynamic page updates.

### Basic request flow
1. You enter a website address or select a link.
2. The browser finds the server's address, often using DNS.
3. The browser sends a request to the server.
4. The server processes the request and sends a response.
5. The browser renders the content and runs permitted scripts.

**Quick revision:** HTML = structure; CSS = appearance; JavaScript = behavior; browser = client; web server = responds to requests.

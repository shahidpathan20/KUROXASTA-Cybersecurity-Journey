# Networking Core Protocols

> Personal study notes from TryHackMe / Cybersecurity 101.

## DNS: REMEMBERING ADDRESSES

A Record = connects a domain name to an IPV4 Address

AAAA Record = connects a domain name to an IPV6 address

CNAME = make one domain name alias of another domain name p[For example: [www.example.com](http://www.example.com) — example.com ]

MX Record = An MX (Mail Exchange) record specifies which mail server is responsible for receiving emails for a domain.

## WHOIS

whois = whois is a command is used to look up publicly available registration information about a domain name or IP address.

## HTTP(S): Accessing the web

- `GET` retrieves data from a server, such as an HTML file or an image.
- `POST` allows us to submit new data to the server, such as submitting a form or uploading a file.
- `PUT` is used to create a new resource on the server and to update and overwrite existing information.
- `DELETE`, as the name suggests, is used to delete a specified file or resource on the server.

## FTP: Transferring Files

FTP

- `USER` is used to input the username
- `PASS` is used to enter the password
- `RETR` (retrieve) is used to download a file from the FTP server to the client.
- `STOR` (store) is used to upload a file from the client to the FTP server.

## SMTP: Sending Mail

SMTP:

- `HELO` or `EHLO` initiates an SMTP session
- `MAIL FROM` specifies the sender’s email address
- `RCPT TO` specifies the recipient’s email address
- `DATA` indicates that the client will begin sending the content of the email message
- `.` is sent on a line by itself to indicate the end of the email message

## POP3: Receiving message

- `USER` identifies the user
- `PASS` provides the user’s password
- `STAT` requests the number of messages and total size
- `LIST` lists all messages and their sizes
- `RETR` retrieves the specified message
- `DELE` marks a message for deletion
- `QUIT` ends the POP3 session applying changes, such as deletions

## IMAP:Synchronizing Email

IMAP

- `LOGIN` authenticates the user
- `SELECT` selects the mailbox folder to work with
- `FETCH` Example `fetch 3 body[]` to fetch message number 3, header and body.
- `MOVE` moves the specified messages to another mailbox
- `COPY` copies the specified messages to another mailbox
- `LOGOUT` logs out

## conclusion

> *Image from the original Notion note was not copied into this Markdown file.*

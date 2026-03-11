# Day 2 – TryHackMe: HTTP in Detail

Room: HTTP in Detail
Platform: TryHackMe

## Overview

This room explains how the HyperText Transfer Protocol (HTTP) works and how web browsers communicate with web servers. HTTP is the core protocol used on the internet to request and transfer web pages, images, and other resources between clients and servers. ([GeeksforGeeks][1])

## What is HTTP?

HTTP stands for HyperText Transfer Protocol. It defines the rules for communication between a client (such as a web browser) and a web server. When a user visits a website, the browser sends an HTTP request to the server, and the server responds with the requested resource. ([GeeksforGeeks][1])

HTTP works using a **request–response model**:

1. The client sends a request to the server.
2. The server processes the request.
3. The server returns a response containing data and a status code. ([BrowserStack][2])

## HTTP Methods

HTTP methods describe the action the client wants to perform on the server.

Common methods include:

* **GET** – Retrieve data from a server.
* **POST** – Send data to the server to create a resource.
* **PUT** – Update an existing resource.
* **DELETE** – Remove a resource from the server. ([Medium][3])

Example:
GET /index.html HTTP/1.1

## HTTP Status Codes

HTTP status codes show whether a request was successful or failed. These codes are grouped into five categories:

* **1xx** – Informational responses
* **2xx** – Successful responses
* **3xx** – Redirection messages
* **4xx** – Client errors
* **5xx** – Server errors ([MDN Web Docs][4])

Examples:

* **200 OK** – Request successful
* **404 Not Found** – Page does not exist
* **500 Internal Server Error** – Server problem

## HTTP Headers

HTTP headers contain extra information about the request or response. They are sent as key-value pairs between the client and server. ([Postman Blog][5])

Examples:

* **Host** – Specifies the requested website
* **User-Agent** – Identifies the browser
* **Content-Type** – Specifies the type of data returned

## Cookies

Cookies are small pieces of data stored in the browser that allow websites to remember user information such as login sessions or preferences. Cookies are usually set by the server using the **Set-Cookie** header and sent back with future requests. ([Wikipedia][6])

## Key Learnings

* How HTTP communication works
* Difference between request and response
* Understanding HTTP methods
* Meaning of HTTP status codes
* Role of headers and cookies in web communication

## Conclusion

This room helped me understand how web communication works using HTTP. Learning these concepts is important for web security and penetration testing because many web vulnerabilities occur through HTTP requests and responses.

[1]: https://www.geeksforgeeks.org/html/what-is-http/?utm_source=chatgpt.com "Hypertext Transfer Protocol - HTTP"
[2]: https://www.browserstack.com/guide/understanding-http?utm_source=chatgpt.com "What Is HTTP: Meaning, Security Threats, and Debugging ..."
[3]: https://medium.com/%40kawsaruddin238/http-in-detail-tryhackme-fb726e12d4a3?utm_source=chatgpt.com "HTTP in detail — TryHackMe - by kawsar uddin"
[4]: https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Status?utm_source=chatgpt.com "HTTP response status codes - MDN Web Docs - Mozilla"
[5]: https://blog.postman.com/what-are-http-headers/?utm_source=chatgpt.com "What are HTTP headers? Request and Response ..."
[6]: https://en.wikipedia.org/wiki/HTTP_cookie?utm_source=chatgpt.com "HTTP cookie"

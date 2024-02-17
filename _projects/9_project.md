---
layout: page
title: "TritonHTTP"
description: Personalized implementation of the HTTP Protocol.
img: assets/img/12.jpg
importance: 1
category: work
related_publications: false
---

TritonHTTP is a simple web server project aimed at implementing a subset of the HTTP/1.1 protocol specification. Built using the Go programming language, TritonHTTP allows clients to connect and retrieve files from the server over a TCP connection. The server is designed to handle multiple client requests concurrently, providing a basic yet functional web server experience.

##### Key Features:

1. [HTTP/1.1 Protocol Implementation](https://www.w3.org/Protocols/HTTP/1.1/draft-ietf-http-v11-spec-01): TritonHTTP adheres to a minimal subset of the HTTP/1.1 protocol specification, supporting essential features such as request/response exchanges, header parsing, and status code handling.

2. [HTTP Persistent Connections](https://en.wikipedia.org/wiki/HTTP_persistent_connection): TritonHTTP supports HTTP persistent connections, enabling clients to reuse TCP connections for multiple request/response interactions. This helps reduce the overhead of establishing new connections for each request.

3. [Virtual Hosting](https://en.wikipedia.org/wiki/Virtual_hosting): The project implements virtual hosting, allowing multiple web servers to be hosted on a single physical machine. Each server is associated with a unique host name and document root directory, enabling the server to serve content based on the "Host" header in the client's request.

4. [Error Handling](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status): TritonHTTP includes robust error handling mechanisms to deal with malformed or invalid client requests. It responds with appropriate HTTP status codes, such as 400 Bad Request and 404 Not Found, to indicate errors to the client.
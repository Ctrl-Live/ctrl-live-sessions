# HTTP/1.1 Client (RFC 7230, RFC 7231)

## Level 1 – Core
- As a user, I want to send HTTP GET requests — so I can retrieve resources from web servers.  
- As a user, I want to set custom request headers — so I can pass authentication tokens and control caching behavior.  

## Level 2 – Extended Methods & Response Handling
- As a user, I want to send POST, PUT, and DELETE requests — so I can interact with APIs that modify data.  
- As a user, I want detailed parsing of response headers (e.g. `Content-Type`, `Cache-Control`) — so I can adapt client behavior based on server metadata.  

## Level 3 – Advanced Features & Performance
- As a user, I want persistent TCP connections with HTTP keep-alive — so I can reduce latency across multiple requests.  
- As a user, I want chunked transfer encoding support — so I can stream large responses without storing them entirely in memory.  

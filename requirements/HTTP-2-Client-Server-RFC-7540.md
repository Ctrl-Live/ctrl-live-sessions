# HTTP/2 Client & Server (RFC 7540)

## Level 1 – Core
- As a user, I want to send and receive HTTP requests over a single multiplexed connection — so I can improve performance.  
- As a user, I want to negotiate HTTP/2 via ALPN — so I can upgrade connections automatically.  

## Level 2 – Stream Control
- As a user, I want to manage stream priorities — so important data loads faster.  
- As a user, I want to handle flow control — so I can manage memory and bandwidth usage efficiently.  

## Level 3 – Optimization
- As a user, I want to support server push — so I can receive resources before I request them.  
- As a user, I want to enable header compression (HPACK) — so I can reduce bandwidth usage.  
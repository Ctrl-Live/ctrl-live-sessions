# WebSocket Client (RFC 6455)

## Level 1 – Core
- As a user, I want to establish a WebSocket connection to a server — so I can send and receive real-time messages.  
- As a user, I want to send text messages in UTF-8 format — so my data is readable by other WebSocket clients and servers.  

## Level 2 – Binary Data & Connection Health
- As a user, I want to send binary data frames — so I can efficiently transmit non-textual information like images or game state.  
- As a user, I want to send periodic ping frames and receive pong responses — so I can detect and close stale connections.  

## Level 3 – Robustness & Extensibility
- As a user, I want to reconnect automatically with exponential backoff — so my client remains stable in case of network issues.  
- As a user, I want to support negotiated extensions (e.g. permessage-deflate) — so I can reduce bandwidth usage.  

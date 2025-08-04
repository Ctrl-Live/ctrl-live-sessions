# Custom DNS Resolver

## Level 1 – Core
- As a developer, I want to send a DNS query to a known resolver — so I can retrieve the IP address of a domain.
- As a developer, I want to parse and print the raw response — so I understand the protocol.

## Level 2 – Manual Packet Construction
- As a developer, I want to construct DNS query packets manually — so I can learn about packet structure.
- As a developer, I want to parse multiple records (A, AAAA, CNAME) — so I understand the variety of responses.

## Level 3 – Scaling: CLI Tool & Timeout Handling
- As a developer, I want to build a CLI tool to resolve domains — so I can use it like `dig`.
- As a developer, I want to handle timeouts and retries — so the tool works reliably over networks.

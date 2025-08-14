# DNS Resolver (RFC 1035)

## Level 1 – Core
- As a user, I want to query DNS servers for A records — so I can resolve domain names to IPv4 addresses.  
- As a user, I want to parse DNS response packets — so I can extract the resolved IP addresses.  

## Level 2 – Extended Record Types & Caching
- As a user, I want to query for AAAA records — so I can retrieve IPv6 addresses.  
- As a user, I want to cache DNS responses respecting TTL values — so I can reduce repeated network lookups.  

## Level 3 – Robustness & Security
- As a user, I want to perform reverse lookups (PTR records) — so I can map IP addresses back to domain names.  
- As a user, I want to validate responses with DNSSEC — so I can ensure the authenticity of DNS data.  
 

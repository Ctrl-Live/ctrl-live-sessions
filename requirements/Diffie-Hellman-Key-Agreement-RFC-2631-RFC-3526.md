# Diffie-Hellman Key Agreement (RFC 2631 + RFC 3526)

## Level 1 – Core
- As a user, I want to perform a finite field Diffie-Hellman key exchange — so I can derive a shared secret over an insecure channel.  
- As a user, I want to use predefined MODP groups from RFC 3526 — so I can rely on well-tested prime parameters.  

## Level 2 – Multiple Group Sizes
- As a user, I want to select group sizes from 1024 to 8192 bits — so I can balance performance and security.  
- As a user, I want to validate received public values — so I can prevent small subgroup attacks.  

## Level 3 – Advanced Integration
- As a user, I want to integrate the DH exchange into a protocol handshake (e.g., CMS, TLS, SSH) — so I can use the derived key for encryption.  
- As a user, I want to store and reuse DH parameters — so I can avoid regenerating primes for each exchange.  

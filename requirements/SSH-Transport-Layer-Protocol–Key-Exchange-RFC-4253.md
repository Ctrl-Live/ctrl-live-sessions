# SSH Transport Layer Protocol – Key Exchange (RFC 4253)

## Level 1 – Core
- As a user, I want to establish a secure SSH session using a key exchange algorithm — so I can protect remote logins and file transfers.  
- As a user, I want to use Diffie-Hellman key exchange — so I can derive a session key over an untrusted network.  

## Level 2 – Algorithm Flexibility
- As a user, I want to use ECDH key exchange for better performance — so I can reduce CPU usage.  
- As a user, I want to select from multiple KEX algorithms (e.g., curve25519-sha256, diffie-hellman-group14-sha256) — so I can match server and client capabilities.  

## Level 3 – Security Hardening
- As a user, I want to disable weak algorithms and enforce strong KEX policies — so I can prevent downgrade attacks.  
- As a user, I want to verify the server’s host key after key exchange — so I can prevent man-in-the-middle attacks.  

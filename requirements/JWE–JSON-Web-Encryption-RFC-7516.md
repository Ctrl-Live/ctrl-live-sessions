# JWE – JSON Web Encryption (RFC 7516)

## Level 1 – Core
- As a user, I want to encrypt a JSON payload into a compact JWE string — so I can securely transmit data.  
- As a user, I want to decrypt a JWE string using my private key — so I can recover the original message.  

## Level 2 – Algorithms & Keys
- As a user, I want to choose between key management algorithms (RSA-OAEP, ECDH-ES) — so I can match my security needs.  
- As a user, I want to choose between content encryption algorithms (AES-GCM, AES-CBC-HMAC) — so I can meet compliance requirements.  

## Level 3 – Advanced Security & Interoperability
- As a user, I want to use JWK (JSON Web Key) for key representation — so I can easily share keys between services.  
- As a user, I want to produce both Compact and JSON serialization forms — so I can support different API expectations.  

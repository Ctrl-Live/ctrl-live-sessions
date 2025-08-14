# Elliptic Curve Diffie-Hellman (ECDH) (RFC 5903 + RFC 7748)

## Level 1 – Core
- As a user, I want to perform ECDH key exchange using standardized curves — so I can establish a shared secret efficiently.  
- As a user, I want to support X25519 and X448 from RFC 7748 — so I can use modern, high-security curves.  

## Level 2 – TLS & Protocol Integration
- As a user, I want to use ECDH as part of a TLS handshake — so I can negotiate secure session keys.  
- As a user, I want to support both static and ephemeral ECDH — so I can choose between performance and forward secrecy.  

## Level 3 – Interoperability & Validation
- As a user, I want to exchange public keys in standardized formats (SEC1, PKCS#8) — so I can interoperate with other software.  
- As a user, I want to validate curve points before use — so I can prevent invalid curve attacks.  

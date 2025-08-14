# HMAC – Keyed-Hash Message Authentication Code (RFC 2104)

## Level 1 – Core
- As a user, I want to compute HMACs over messages using a shared secret key — so I can verify message integrity.  
- As a user, I want to choose from multiple hash algorithms (e.g., SHA-256, SHA-512) — so I can meet security requirements.  

## Level 2 – Verification & Encoding
- As a user, I want to verify a received HMAC against a computed one — so I can detect tampering.  
- As a user, I want to output HMACs in hexadecimal and Base64 formats — so I can match different API requirements.  

## Level 3 – Advanced Security
- As a user, I want to use constant-time comparison when verifying HMACs — so I can prevent timing attacks.  
- As a user, I want to derive HMAC keys securely from passwords using PBKDF2 — so I avoid weak key material.  

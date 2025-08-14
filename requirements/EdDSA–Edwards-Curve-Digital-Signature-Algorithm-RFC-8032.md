# EdDSA – Edwards-Curve Digital Signature Algorithm (RFC 8032)

## Level 1 – Core
- As a user, I want to generate Ed25519 key pairs — so I can sign messages securely.  
- As a user, I want to sign messages and produce compact signatures — so I can ensure authenticity.  

## Level 2 – Verification & Variants
- As a user, I want to verify Ed25519 signatures — so I can confirm messages came from the expected signer.  
- As a user, I want to use Ed448 for higher security — so I can meet stricter cryptographic policies.  

## Level 3 – Advanced Usage
- As a user, I want to store and load keys in standard formats (PEM, DER) — so I can interoperate with other tools.  
- As a user, I want to sign and verify large data streams — so I can handle files without loading them entirely in memory.  

# X.509 Certificates and CRLs (RFC 5280)

## Level 1 – Core
- As a user, I want to parse X.509 certificates — so I can extract public keys, issuer, and subject information.  
- As a user, I want to verify certificate signatures — so I can confirm they were issued by a trusted CA.  

## Level 2 – Revocation & Validation
- As a user, I want to parse and process Certificate Revocation Lists (CRLs) — so I can detect revoked certificates.  
- As a user, I want to validate certificate chains — so I can ensure the end-entity certificate is trusted.  

## Level 3 – Advanced Features
- As a user, I want to handle extensions like Subject Alternative Name — so I can validate multi-domain and wildcard certificates.  
- As a user, I want to enforce certificate validity periods — so expired certificates are rejected.  

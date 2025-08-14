# Certificate Signing Requests (PKCS #10, RFC 2986)

## Level 1 – Core
- As a user, I want to generate a Certificate Signing Request (CSR) with my public key — so I can request a certificate from a CA.  
- As a user, I want to include subject information in the CSR — so the certificate contains my identity details.  

## Level 2 – Extensions & Formats
- As a user, I want to include extensions like SAN in the CSR — so I can request multi-domain certificates.  
- As a user, I want to export CSRs in PEM and DER formats — so they can be submitted to different CAs.  

## Level 3 – Security & Automation
- As a user, I want to sign the CSR with my private key — so the CA can verify ownership of the key.  
- As a user, I want to script CSR generation — so I can automate large-scale certificate requests.  

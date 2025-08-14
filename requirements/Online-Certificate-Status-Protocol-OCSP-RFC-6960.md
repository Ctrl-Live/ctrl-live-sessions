# Online Certificate Status Protocol (OCSP, RFC 6960)

## Level 1 – Core
- As a user, I want to send an OCSP request for a certificate — so I can check if it is revoked.  
- As a user, I want to parse and interpret OCSP responses — so I can know the certificate’s status.  

## Level 2 – Security & Verification
- As a user, I want to verify the OCSP response signature — so I can confirm it comes from a trusted responder.  
- As a user, I want to handle nonce values in OCSP requests — so I can prevent replay attacks.  

## Level 3 – Performance & Integration
- As a user, I want to cache OCSP responses until they expire — so I can reduce repeated lookups.  
- As a user, I want to integrate OCSP checks into my TLS handshake — so certificates are validated automatically on connection.  

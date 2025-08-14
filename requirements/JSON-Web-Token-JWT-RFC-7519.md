# JSON Web Token (JWT) (RFC 7519)

## Level 1 – Core
- As a user, I want to create and sign JWTs — so I can securely transmit claims between parties.  
- As a user, I want to verify JWT signatures — so I can confirm authenticity.  

## Level 2 – Claims & Expiration
- As a user, I want to include standard claims (`iss`, `sub`, `exp`) — so I can ensure token interoperability.  
- As a user, I want to reject expired tokens — so I can prevent unauthorized access.  

## Level 3 – Advanced Security
- As a user, I want to use asymmetric key signing (RS256) — so I can validate tokens without sharing private keys.  
- As a user, I want to encrypt JWTs (JWE) — so I can protect sensitive claims in transit.  

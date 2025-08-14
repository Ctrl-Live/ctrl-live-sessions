# Internet Key Exchange Protocol Version 2 (IKEv2, RFC 7296)

## Level 1 – Core
- As a user, I want to establish an IPsec security association using IKEv2 — so I can encrypt network traffic securely.  
- As a user, I want to perform mutual authentication using pre-shared keys or certificates — so I can verify both ends of the connection.  

## Level 2 – Key Exchange & Rekeying
- As a user, I want to negotiate Diffie-Hellman or ECDH key exchange during the handshake — so I can derive shared encryption keys.  
- As a user, I want to rekey existing security associations without dropping traffic — so I can maintain secure sessions over time.  

## Level 3 – Advanced Features
- As a user, I want to support MOBIKE (Mobility and Multihoming) — so VPN connections survive IP address changes.  
- As a user, I want to integrate IKEv2 with a PKI system — so I can use CA-issued certificates for authentication.   

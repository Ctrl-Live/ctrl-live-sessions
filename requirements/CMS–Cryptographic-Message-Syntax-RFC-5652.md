# CMS – Cryptographic Message Syntax (RFC 5652)

## Level 1 – Core
- As a user, I want to encrypt data with CMS EnvelopedData — so I can send confidential messages.  
- As a user, I want to sign data with CMS SignedData — so I can ensure authenticity and integrity.  

## Level 2 – Multiple Recipients & Detached Signatures
- As a user, I want to encrypt to multiple recipients — so each can decrypt with their own private key.  
- As a user, I want to produce detached signatures — so I can sign data without embedding the content.  

## Level 3 – Interoperability
- As a user, I want to handle CMS data in PEM and DER encodings — so I can work with existing PKI tools.  
- As a user, I want to validate certificate chains in CMS signatures — so I can ensure signers are trusted.  

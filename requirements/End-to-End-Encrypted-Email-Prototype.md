# End-to-End Encrypted Email Prototype

## Level 1 – Core
- As a user, I want to generate a public/private keypair — so I can receive encrypted messages.
- As a sender, I want to encrypt messages with the recipient’s public key — so only they can read it.

## Level 2 – Message Signing
- As a user, I want to digitally sign messages — so the recipient can verify I sent it.
- As a recipient, I want to verify signatures using the sender's public key — so I can detect tampering.

## Level 3 – Scaling: Key Directory & Attachments
- As a user, I want to fetch public keys from a directory — so I don't need to exchange them manually.
- As a user, I want to encrypt and send attachments — so documents stay private too.

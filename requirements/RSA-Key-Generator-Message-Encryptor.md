# RSA Key Generator & Message Encryptor

## Level 1 – Core
- As a user, I want to generate a public/private key pair — so I can encrypt and decrypt messages.
- As a user, I want to encrypt a message with a public key — so only the private key can decrypt it.

## Level 2 – Key Storage & Export
- As a user, I want to save keys to disk — so I can reuse them later.
- As a user, I want to export the public key in PEM format — so others can send me encrypted messages.

## Level 3 – Scaling: Key Expiry & Identity
- As a user, I want to assign an identity (email, name) to a key — so I can track who owns what.
- As a developer, I want to include an expiry timestamp in the key file — so users can rotate keys.

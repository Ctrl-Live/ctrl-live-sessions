# Perfect Forward Secrecy Chat Playground

## Level 1 – Core
- As a user, I want to start a chat where each message uses a new key — so past messages can't be decrypted even if a key leaks.
- As a user, I want messages to expire after viewing — so chats are ephemeral.

## Level 2 – One-Time Session Keys
- As a developer, I want to derive session keys from DH exchanges — so conversations are forward-secure.
- As a user, I want to simulate message deletion on both ends — so no trace is left.

## Level 3 – Scaling: Asynchronous Delivery & Offline Mode
- As a user, I want to send a message to someone who is offline — so they can read it later securely.
- As a developer, I want pre-keys to enable this delayed delivery — so no user has to stay online.

# Signal Protocol: Double Ratchet Simulation

## Level 1 – Core
- As a user, I want to send encrypted messages between two users using a shared key — so I can simulate secure chat.
- As a developer, I want to derive a new key per message (ratchet forward) — so past messages can't be decrypted if a key is compromised.

## Level 2 – Key Rotation & One-Time Pre-keys
- As a developer, I want to simulate identity keys, ephemeral keys, and pre-keys — so users can start conversations asynchronously.
- As a user, I want to rotate keys after each message — so security improves with every exchange.

## Level 3 – Scaling: Store Conversation State & Lost Messages
- As a user, I want to store state across messages — so I can resume a conversation securely.
- As a developer, I want to simulate message loss and recovery — so I can test protocol resilience.

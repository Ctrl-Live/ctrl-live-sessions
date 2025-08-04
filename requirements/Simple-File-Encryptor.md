# Simple File Encryptor

## Level 1 – Core
- As a user, I want to input a file and a password — so I can encrypt the file securely.
- As a user, I want to decrypt the file using the same password — so I can recover the original content.

## Level 2 – Password Handling
- As a developer, I want to derive a key from the password using a KDF (e.g., PBKDF2 or scrypt) — so brute-force resistance is improved.
- As a user, I want to be warned if the password is wrong — so I don't decrypt garbage.

## Level 3 – Scaling: Multiple Files & Drag-and-Drop
- As a user, I want to encrypt/decrypt multiple files in batch — so I save time.
- As a user, I want a simple UI (or CLI) with drag-and-drop — so it's easier to use across platforms.

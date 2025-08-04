# Broken Authentication Demo

## Level 1 – Core
- As a user, I want to log in with a session cookie — so I can stay authenticated.
- As a tester, I want to reuse session IDs across devices — so I can hijack sessions.

## Level 2 – Weak Passwords & Bruteforce
- As a user, I want to test multiple login attempts — so I can simulate brute force attacks.
- As a tester, I want to use a known weak password — so I can bypass with common credentials.

## Level 3 – Scaling: Session Expiry & MFA
- As a developer, I want sessions to expire after inactivity — so stale tokens are revoked.
- As a user, I want a second authentication step — so access is hardened.

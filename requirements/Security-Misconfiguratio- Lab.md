# Security Misconfiguration Lab

## Level 1 – Core
- As a user, I want to view public debug information — so I can identify exposed server internals.
- As a tester, I want to access admin endpoints — so I can exploit overly permissive routes.

## Level 2 – Directory Browsing & Headers
- As a user, I want to view directory listings — so I can access unintended files.
- As a developer, I want to simulate missing security headers — so I can show risks like clickjacking or MIME sniffing.

## Level 3 – Scaling: Harden Config & Deployment Modes
- As a developer, I want to disable debug mode in production — so secrets aren’t exposed.
- As a user, I want to verify config changes reduce attack surface — so I can confirm patches work.

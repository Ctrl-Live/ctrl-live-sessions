# Webhook Listener & Forwarder

## Level 1 – Core
- As a user, I want to receive POST requests at a public endpoint — so I can test webhooks.
- As a developer, I want to log incoming data — so I can inspect payloads.

## Level 2 – Replay & Forwarding
- As a user, I want to replay previous payloads — so I can retest integrations.
- As a developer, I want to forward incoming data to another URL — so I can chain services.

## Level 3 – Scaling: Retry Policies & Authentication
- As a system, I want to retry failed forwards with backoff — so data isn’t lost due to transient issues.
- As a user, I want to require a secret token — so only trusted sources can send webhooks.

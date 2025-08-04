# ICMP Ping Implementation

## Level 1 – Core
- As a developer, I want to send an ICMP echo request to a host — so I can test reachability.
- As a developer, I want to receive the echo reply and show roundtrip time — so I can measure latency.

## Level 2 – Packet Details
- As a developer, I want to construct ICMP packets manually — so I understand the format.
- As a developer, I want to verify checksums — so the packets are valid.

## Level 3 – Scaling: CLI Options & Parallel Pings
- As a user, I want to ping multiple hosts in parallel — so I can diagnose network health.
- As a user, I want CLI options like `-c` for count and `-t` for timeout — so I have control.

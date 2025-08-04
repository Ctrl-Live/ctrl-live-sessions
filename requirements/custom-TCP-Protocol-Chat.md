# Custom TCP Protocol Chat

## Level 1 – Core
- As a user, I want to connect to a server and send/receive text messages — so I can chat in real-time.
- As a user, I want to see who else is online — so I know I’m not alone.

## Level 2 – Protocol Features
- As a user, I want to send `/nick` to change my display name — so I can personalize my identity.
- As a user, I want to handle `PING`/`PONG` messages — so the connection stays alive.

## Level 3 – Scaling: Authentication & Reconnect
- As a user, I want to authenticate with a username/password — so the chat is secure.
- As a user, I want to auto-reconnect if disconnected — so I stay in the chat during blips.

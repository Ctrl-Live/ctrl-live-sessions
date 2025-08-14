# OAuth 2.0 Client (RFC 6749)

## Level 1 – Core
- As a user, I want to obtain an access token using the Authorization Code flow — so I can authenticate to APIs on behalf of a user.  
- As a user, I want to securely store the access token — so I can reuse it without re-authentication until it expires.  

## Level 2 – Token Management & Other Flows
- As a user, I want to refresh expired tokens using a refresh token — so I can maintain API access without requiring user re-login.  
- As a user, I want to implement the Client Credentials flow — so I can authenticate machine-to-machine services.  

## Level 3 – Security & Advanced Use
- As a user, I want to use PKCE (Proof Key for Code Exchange) — so I can secure public clients like mobile apps against code interception.  
- As a user, I want to support token introspection and revocation — so I can validate token status and log users out immediately if needed.  

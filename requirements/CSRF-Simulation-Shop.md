# CSRF Simulation Shop

## Level 1 – Core
- As a user, I want to log into a shop and update my email — so I can personalize my profile.
- As a tester, I want to craft a hidden form on another site that submits to the shop — so I can demonstrate CSRF.

## Level 2 – GET-Based and Cookie-Based Attacks
- As a tester, I want to perform a GET request with query params — so I can simulate CSRF on unsafe methods.
- As a user, I want to see my cookie reused automatically — so CSRF works without user action.

## Level 3 – Scaling: CSRF Tokens & SameSite
- As a developer, I want to implement CSRF tokens — so only valid forms succeed.
- As a developer, I want to set the `SameSite` flag on cookies — so the browser rejects cross-origin requests.

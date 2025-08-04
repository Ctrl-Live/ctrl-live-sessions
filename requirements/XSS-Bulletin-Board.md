# XSS Bulletin Board

## Level 1 – Core
- As a user, I want to post messages to a shared board — so others can read them.
- As a tester, I want to inject `<script>` tags into the message — so I can trigger XSS on page load.

## Level 2 – Stored & Reflected XSS
- As a user, I want a search field that echoes my query — so I can test reflected XSS.
- As a user, I want to preview posts before submitting — so I can test stored XSS in form previews.

## Level 3 – Scaling: Escaping & Content Security Policy
- As a developer, I want to sanitize input on display — so XSS is neutralized at render time.
- As a developer, I want to implement a basic CSP header — so the browser blocks inline scripts.

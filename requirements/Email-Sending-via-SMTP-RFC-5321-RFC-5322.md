# Email Sending via SMTP (RFC 5321, RFC 5322)

## Level 1 – Core
- As a user, I want to connect to an SMTP server and send plain-text emails — so I can deliver messages to recipients.  
- As a user, I want to validate email addresses against RFC 5322 syntax — so I avoid invalid recipient errors.  

## Level 2 – Security & Attachments
- As a user, I want to send emails over TLS (STARTTLS) — so my communication is encrypted in transit.  
- As a user, I want to attach files with proper MIME encoding — so recipients can open images, documents, and media files.  

## Level 3 – Reliability & Compliance
- As a user, I want to implement SMTP authentication (AUTH LOGIN, AUTH PLAIN) — so only authorized senders can use my service.  
- As a user, I want to handle and log bounce messages — so I can track undelivered mail and take corrective action.  

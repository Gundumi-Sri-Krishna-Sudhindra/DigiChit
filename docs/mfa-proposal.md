# Multi-Factor Authentication (MFA) Proposal

Technical specification for introducing Time-based One-Time Passwords (TOTP).

## Flow
1. User scans QR code using Authenticator app (Google Authenticator, Authy).
2. 6-digit TOTP token validated on backend.
3. Recovery codes generated and downloaded securely.

### Security Standard
Implementation conforms to RFC 6238 TOTP specifications with SHA-1 HMAC and 30s window.

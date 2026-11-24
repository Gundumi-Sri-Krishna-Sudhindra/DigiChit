# Audit Logging & Compliance

All financial transactions, administrative actions, and state changes are immutable logs.

## Audit Fields
- `timestamp`: UTC timestamp of event.
- `actorId`: User or system ID triggering event.
- `actionType`: Verb designating operation.
- `metadata`: Snapshot of previous and updated states.

### Retention Period
Audit logs are retained for a minimum of 7 years in compliance with financial regulations.

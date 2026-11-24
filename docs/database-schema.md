# Database Schema & Relationships

DigiChit models relationships using MongoDB collections.

## Collections
- `users`: User credentials, profile data, and roles.
- `chitgroups`: Group metadata, duration, installments, member lists.
- `cycles`: Per-month bidding sessions, winner id, discount pool.
- `ledgerentries`: Journal entries, debit/credit legs, balance tracking.

### Foreign Key References
All entity relations use ObjectId references with indexed foreign fields for high performance.

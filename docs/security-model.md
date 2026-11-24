# Security and Role-Based Access Control (RBAC)

DigiChit protects all administrative and financial actions using JWT tokens and strict role checks.

## User Roles
- **Admin / Organizer**: Group creation, parameter adjustment, offline payment approvals.
- **Member**: View enrolled groups, participate in bidding, submit installment payments.
- **Auditor**: Read-only access to ledger statements and compliance logs.

### Token Expiry
Access tokens expire in 15 minutes; refresh tokens are securely rotated with 7-day TTL.

## Permissions Matrix

| Permission | Admin | Member | Guest |
|---|---|---|---|
| View Public Chits | Yes | Yes | Yes |
| Place Auction Bid | No | Yes | No |
| Approve Offline Payment | Yes | No | No |
| Export Audit Log | Yes | No | No |

Note: Admins cannot participate as bidders in their own managed chit funds.

# Error Code Catalog & Troubleshooting

Standardized application error classifications.

## Error Categories
- `ERR_AUTH_*`: Authentication, token expiration, invalid credentials.
- `ERR_CHIT_*`: Invalid cycle state, auction closed, duplicate registration.
- `ERR_PAYMENT_*`: Gateway rejection, signature mismatch, duplicate settlement.
- `ERR_LEDGER_*`: Unbalanced debit/credit sum, account not found.

### HTTP Mappings
`ERR_AUTH_*` maps to 401/403, `ERR_CHIT_*` and `ERR_PAYMENT_*` map to 400/422.

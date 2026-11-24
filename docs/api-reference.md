# REST API Reference

The DigiChit backend provides RESTful endpoints organized by domain.

## Endpoints
- `POST /api/auth/login`: User authentication
- `POST /api/auth/register`: User onboarding
- `GET /api/chits`: List active chits
- `POST /api/chits`: Create new chit group
- `GET /api/ledger/entries`: Retrieve ledger transactions

### Standard Error Codes
- 400 Bad Request
- 401 Unauthorized
- 403 Forbidden
- 404 Not Found
- 500 Internal Error

# Payment Gateway Integration (Razorpay)

DigiChit integrates with Razorpay for member installment collections.

## Payment Flow
1. User clicks 'Pay Now' for due cycle installment.
2. Backend creates order via Razorpay API.
3. Frontend loads Razorpay checkout modal with order details.
4. On success, signature is validated on backend and ledger entry is posted.

### Webhook Validation
HMAC SHA256 signature verification protects webhook endpoints against tampering.

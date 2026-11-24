# Installment Schedules & Grace Periods

Specification of monthly collection rules and penalties.

## Rules
- Installments become due on the 1st of every month.
- Grace period lasts until the 10th of the month without penalty.
- Late payment interest is logged as a separate penalty ledger account if configured.

### Weekend / Holiday Adjustment
If the 10th falls on a public banking holiday, the grace period extends to the next business day.

# Cron Jobs & Scheduled Tasks Catalog

Automated background schedules executed by the server worker.

## Schedules
- **Daily Midnight**: Check for upcoming auctions and dispatch email notifications.
- **Daily 9 AM**: Send payment reminders for pending monthly installments.
- **Hourly**: Check for stale pending Razorpay transactions and synchronize status.

### Cron Syntax
All jobs use standard 5-part cron syntax (e.g. `0 0 * * *` for midnight UTC).

# Disaster Recovery & Backup Runbook

Procedures for emergency response and automated daily snapshots.

## Backup Strategy
- Automated daily MongoDB dumps stored in S3/Cloud Storage.
- Point-in-time recovery enabled with continuous oplog archiving.
- Annual recovery testing drill procedures.

### Restore Command
Execute: `mongorestore --drop --uri="$MONGODB_URI" /path/to/backup/dir`

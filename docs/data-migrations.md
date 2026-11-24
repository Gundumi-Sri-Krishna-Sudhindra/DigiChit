# Database Migrations and Data Seeding

Guidelines for running schema upgrades and initial seeding.

## Scripts
- `migrateFinancialConfig`: Normalizes legacy chit configurations to current schemas.
- `seedInitialData`: Provisions root admin and test accounts.

### Backup and Rollback Procedure
Always run `mongodump` prior to executing schema migration scripts.

# Performance Tuning and Optimization

Best practices for ensuring sub-100ms response times across DigiChit.

## Areas
- MongoDB Index optimization on `chitId`, `cycleId`, and `userId` fields.
- In-memory caching for live bid states during active auctions.
- Gzip compression and static asset bundle chunking via Vite.

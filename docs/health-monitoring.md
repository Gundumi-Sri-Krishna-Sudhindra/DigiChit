# System Health & Monitoring

Observability guidelines and endpoint probes for uptime tracking.

## Health Probes
- `GET /api/health`: Basic liveness probe returning HTTP 200.
- `GET /api/health/ready`: Readiness probe verifying MongoDB connectivity and Redis cache.

### Probe Frequency
Kubernetes or load balancer probes should ping `/health` at 15-second intervals with a 5s timeout.

# daemon decommissioning

## Infrastructure
Configuration for daemon decommissioning component (ref 8).

## Deployment
- Replicas: 2-5
- Memory: 256Mi-512Mi
- CPU: 100m-500m

## Monitoring
- Prometheus: :9090/metrics
- Alert: p99 > 500ms

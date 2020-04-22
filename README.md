# Description

This role configures [M3DB](https://www.m3db.io/) Coordinator as a Prometheus backend.

__WARNING__: This was abandoned in favor of InfluxDB.

# Configuration

And M3 cluster of DB nodes depends on an ETCD cluster.
```yaml
m3_coordinator_etcd_service_name: 'etcd'
m3_coordinator_service_name: 'm3coordinator'
m3_coordinator_service_user: 'nobody'
```

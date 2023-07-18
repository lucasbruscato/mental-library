Route 53 is a managed [[DNS (domain name system)]], it has multiple routing policies, they are:

1. **Simple routing policy**: no health checks are applied, single route.
2. **Weighted routing policy**: Route 53 can divide the flow into several weights, for example, 70% to instance 1, 20% to instance 2 and 10% to instance 3.
3. **Latency routing policy**: Route 53 will redirect to the closest geographic server.
4. **Failover routing policy**: it will perform a health check on the `primary` instance, if something goes badly it will forward to the `failover` instance.

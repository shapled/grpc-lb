> fork from [liyue201/grpc-lb](https://github.com/liyue201/grpc-lb)

# grpc-lb
This is a gRPC load balancing library for go.

 ![](/architecture.png)
 
## Feature
- supports Random, RoundRobin, LeastConnection and ConsistentHash strategies.
- supports <del>[etcd](https://github.com/etcd-io/etcd), [consul](https://github.com/consul/consul) and</del> [zookeeper](https://github.com/apache/zookeeper) as a registry.

## Example
- [examples - zookeeper - server](/examples/zookeeper/server)
- [examples - zookeeper - client](/examples/zookeeper/client)

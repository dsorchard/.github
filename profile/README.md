## 🌱 The Foundation

<details>
<summary>Read More</summary>

#### Core Distributed Systems Algorithms from [Wiki](https://en.wikipedia.org/wiki/Distributed_algorithm)
- [Atomic Commit](https://github.com/dsorchard/two_pc): 2 phase commit, replica, atomic commit
- Consensus: Paxos, Raft
- [Leader Election](https://github.com/dsorchard/distributed_leader_election): `Layered BFS`, `Flood Max` 
- Mutual Exclusion: Chubby Lock vs [Theory Dist. Locks](https://github.com/dsorchard/Distributed-MutualExclusion)
- [Reliable Broadcast](https://github.com/dsorchard/swim_impl): SWIM, gossip, disseminator, incarnation
- Replication: RAID, Deduplicate, CRDT
- Retry Strategy: At least once, At most once, Exactly once
- Spanning Tree: MST
- Symmetry breaking:
- [Snapshot](https://github.com/dsorchard/distributed_snapshot.git): Chandy-Lamport, Vector Clock, VRPC (library)
- Synchronizer:
- Clocks: Vector Clock, Matrix Clock, HLC
- Checkpointing and Recovery: Koo and Toueg’s Protocol

#### More Distributed Systems Concepts
- HA/keepalive: Central Service, HA state added to multi-raft
- RPC client: socket, RPC, DMA, RDMA, REST, n/w protocols
- Load balancer proxy/Fanout: Prometheus, JunoDB
- Shuffling: Spark, Uber's Remote Shuffling Service
- Resource Allocation: Spark Resource Allocator, Dead Lock Detection using Resource Allocation Graph

#### Popular Library Usage

- [Hashicorp Gossip & Consistent Hashing](https://github.com/dsorchard/dist_kv): Gossip, Consistent Hashing, Virtual Node, Replication, Rebalancing
- [Hashicorp Raft](https://github.com/dsorchard/raft_kv): Raft, Not Multi Raft
- Etcd Membership/Lock:
- DragonBoat Multi Raft: Multi Raft, Sharding
- Snapshot: Distributed Snapshot
- 2PC or Saga: Txn, 2PC
- DistributedClocks GoVector: Use DistributedClocks/GoVector
- lafikl HLC: Use lafikl/hlc
- Client + HLC: Read your writes
- Chord Distributed Hash Table

#### Misc
- [embedded server](https://github.com/dsorchard/tiny-embedded-server): `Sockets`
- [geo-spark-lite](https://github.com/dsorchard/spatial-spark-rdd): `Spark RDD`, `Apache Sedona`, `Spatial Indexing`
- [network topology optimizer](https://github.com/dsorchard/network_topology_optimizer): `Heuristics`, `Topology`

</details>

## 🌿 The Plant
> Source: Components extracted from real-world distributed database

<details>
<summary>Read More</summary>

#### Individual components
- Raft WAL
- [Distributed Gossip Cache](https://github.com/dsorchard/gossipcache): Gossip, Consistent Hashing, LRU
- Distributed Txn
- VFS: From Dragonboat library
- HA Checker
- Load Balancer Proxy

#### MatrixOrigin Parts
- RAFT Log Service
- Distributed Gossip Cache
- RPC Client
- Distributed Txn

#### E2E Products
- Distributed KV Store: 2PC, Gossip, Consistent/Range Partitioning, RAFT WAL, HA, Etcd, Proxy (load balancer), Stats
- Distributed Execution Engine: Like Spark, VFS, Cache, Process, Checkpointing, Snapshot, Rate Limiting
- Distributed Query Engine: 2PC, RPC module, VRPC tracing, Catalog, Agg Fn, Binder, Type Coercion, Use Stats in Optimizer

#### Shrunk Distributed Database Systems
- [junodb-lite](https://github.com/dsorchard/junodb_lite): KV Server, Distributed System, Etcd
- Etcd Lite

</details>

## 🌳 The Tree
> Source: The popular services for Storage, Compute, and Networks.

<details>
<summary>Read More</summary>

#### Distributed Database/Cache/Storage Systems
- JunoDB
- Etcd
- Apache Omid
- Cluster Manager (Apache Helix)

#### Misc Distributed Systems
- Spark (Apache Hudi)
- Kafka
</details>

## 💧 The Resources
> Learn the concepts. Build examples. Defend your understanding.

<details>
<summary>Read More</summary>

#### Books
- [Patterns of Distributed Systems](https://martinfowler.com/articles/patterns-of-distributed-systems/) - `Spanner` 2PC etc.
- [Designing Data-Intensive Applications](https://a.co/d/hwmSC1o)

#### Papers
- Dynamo Paper
- Chord DT Paper
- SWIM Paper
</details>

## 👨‍🌾 Cultivating Knowledge
> Give talks or discussions. Pending.

<details>
<summary>Read More</summary>

#### Published Resources
- [Using spark for spatial data management](https://medium.com/sys-base/spatial-partitioned-rdd-using-kd-tree-in-spark-102e0b53564b) - Spark RDD, KD Tree

</details>

## 🥭 The Fruit
> Mark the milestones.

<details>
<summary>Read More</summary>

</details>

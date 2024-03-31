## 🌱 The Foundation
> Get the basics right.

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
- [Snapshot](https://github.com/dsorchard/distributed_snapshot.git): Chandy-Lamport, Vector Clock, VRPC (library)
- Clocks: Vector Clock, Matrix Clock, HLC

#### More Distributed Systems Concepts
- HA/keepalive: Central Service, HA state added to multi-raft
- RPC client: socket, RPC, GRPC, DMA, RDMA, REST, n/w protocols, Arrow RPC, GORM
- Load balancer proxy/Fanout: Prometheus, JunoDB
- Shuffling: Spark, Uber's Remote Shuffling Service
- Resource Allocation: Spark Resource Allocator, Dead Lock Detection using Resource Allocation Graph
- Checkpointing and Recovery: Koo and Toueg’s Protocol
- Synchronizer: Physical clock synchronization 
- Symmetry breaking: Leader election in Ring
- Multi-Tenant Systems: Sharing one instance with many users. Adding TenantId prefix to resource access calls.
- Distributed Rate Limiter: Make be reference [this](https://github.com/fagongzi/distributed-limiter/tree/master)
- Scheduling: Quartz, DAG, Dead-lock

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
- Chord Distributed Hash Table vs Locality Sensitive Hashing: Read more in [Wiki](https://en.wikipedia.org/wiki/Distributed_hash_table)  

#### Misc
- [embedded server](https://github.com/dsorchard/tiny-embedded-server): `Sockets`
- [geo-spark-lite](https://github.com/dsorchard/spatial-spark-rdd): `Spark RDD`, `Apache Sedona`, `Spatial Indexing`
- [network topology optimizer](https://github.com/dsorchard/network_topology_optimizer): `Heuristics`, `Topology`

</details>

## 🌿 The Plant
> Read, Extract components, and Learn the inner workings.

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
- Distributed File Store: Maybe like HDFS, SeaweedFS, JuiceFS

#### Shrunk Distributed DB's
- [junodb-lite](https://github.com/dsorchard/junodb_lite): KV Server, Distributed System, Etcd
- Etcd Lite

#### Industry Tool Usage: (Networking, Compute, Storage)
- Networking: Kubernetes Operator
- Compute: Spark
- Storage: RocksDB, HDFS
- Observability:
- Tracing:

</details>

## 🌳 The Tree
> Pick your favorite distributed database/system and shrink it.

<details>
<summary>Read More</summary>

#### Distributed Database/Cache/Storage Systems
- JunoDB
- Etcd
- MatrixOrigin
- TiDB
- CockroachDB

</details>

## 💧 The Resources
> Revisit papers/slides. Build counterexamples. Think like a scientist.

<details>
<summary>Read More</summary>

#### Books
- [Patterns of Distributed Systems](https://martinfowler.com/articles/patterns-of-distributed-systems/) - `Spanner` 2PC etc.
- [Designing Data-Intensive Applications](https://a.co/d/hwmSC1o)

#### Papers read
- Dynamo Paper
- SWIM Paper
- Spanner Paper

#### Papers [Pending]
- Chord DT Paper

</details>

## 👨‍🌾 Cultivating Knowledge
> Write what you understood. (Maybe later)

<details>
<summary>Read More</summary>

#### Published Resources
- [Using spark for spatial data management](https://medium.com/sys-base/spatial-partitioned-rdd-using-kd-tree-in-spark-102e0b53564b) - Spark RDD, KD Tree

</details>

## 🥭 The Fruit
> Mark your achievements.

<details>
<summary>Read More</summary>

</details>

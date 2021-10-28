//[alchemist](../../index.md)/[it.unibo.alchemist.grid.cluster](index.md)

# Package it.unibo.alchemist.grid.cluster

## Types

| Name | Summary |
|---|---|
| [Cluster](-cluster/index.md) | [jvm]<br>interface [Cluster](-cluster/index.md) : [AutoCloseable](https://docs.oracle.com/javase/8/docs/api/java/lang/AutoCloseable.html)<br>The entity that represent the joined cluster. |
| [ClusterImpl](-cluster-impl/index.md) | [jvm]<br>class [ClusterImpl](-cluster-impl/index.md) : [Cluster](-cluster/index.md)<br>An implementation of [Cluster](-cluster/index.md) uses Apache Ignite. |
| [WorkerSet](-worker-set/index.md) | [jvm]<br>interface [WorkerSet](-worker-set/index.md)<br>Set of remote nodes that can run simulations. |
| [WorkerSetImpl](-worker-set-impl/index.md) | [jvm]<br>class [WorkerSetImpl](-worker-set-impl/index.md) : [WorkerSet](-worker-set/index.md)<br>Implementation of [WorkerSet](-worker-set/index.md) which uses Apache Ignite. |

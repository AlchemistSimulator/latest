//[alchemist](../../../index.md)/[it.unibo.alchemist.grid.cluster](../index.md)/[Cluster](index.md)

# Cluster

[jvm]\
interface [Cluster](index.md) : [AutoCloseable](https://docs.oracle.com/javase/8/docs/api/java/lang/AutoCloseable.html)

The entity that represent the joined cluster.

## Functions

| Name | Summary |
|---|---|
| [close](close.md) | [jvm]<br>abstract fun [close](close.md)()<br>Leave the cluster. |
| [getWorkersSet](get-workers-set.md) | [jvm]<br>abstract fun [getWorkersSet](get-workers-set.md)(complexity: [Complexity](../../it.unibo.alchemist.grid.simulation/-complexity/index.md)): [WorkerSet](../-worker-set/index.md)<br>a simulation's complexity |

## Inheritors

| Name |
|---|
| [ClusterImpl](../-cluster-impl/index.md) |

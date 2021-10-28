//[alchemist](../../../index.md)/[it.unibo.alchemist.grid.cluster](../index.md)/[ClusterImpl](index.md)

# ClusterImpl

[jvm]\
class [ClusterImpl](index.md) : [Cluster](../-cluster/index.md)

An implementation of [Cluster](../-cluster/index.md) uses Apache Ignite.

## Constructors

| | |
|---|---|
| [ClusterImpl](-cluster-impl.md) | [jvm]<br>open fun [ClusterImpl](-cluster-impl.md)(configPath: [Path](https://docs.oracle.com/javase/8/docs/api/java/nio/file/Path.html))<br>path of Ignite's configuration file |

## Functions

| Name | Summary |
|---|---|
| [close](close.md) | [jvm]<br>open fun [close](close.md)()<br>Leave the cluster.<br>[jvm]<br>abstract fun [close](index.md#-1117130810%2FFunctions%2F-267951372)() |
| [getWorkersSet](get-workers-set.md) | [jvm]<br>open fun [getWorkersSet](get-workers-set.md)(complexity: [Complexity](../../it.unibo.alchemist.grid.simulation/-complexity/index.md)): [WorkerSet](../-worker-set/index.md)<br>a simulation's complexity |

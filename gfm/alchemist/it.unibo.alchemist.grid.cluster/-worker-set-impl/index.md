//[alchemist](../../../index.md)/[it.unibo.alchemist.grid.cluster](../index.md)/[WorkerSetImpl](index.md)

# WorkerSetImpl

[jvm]\
class [WorkerSetImpl](index.md) : [WorkerSet](../-worker-set/index.md)

Implementation of [WorkerSet](../-worker-set/index.md) which uses Apache Ignite.

## Constructors

| | |
|---|---|
| [WorkerSetImpl](-worker-set-impl.md) | [jvm]<br>open fun [WorkerSetImpl](-worker-set-impl.md)(ignite: Ignite, grp: ClusterGroup)<br>Ignite instance |

## Functions

| Name | Summary |
|---|---|
| [distributeSimulations](distribute-simulations.md) | [jvm]<br>open fun [distributeSimulations](distribute-simulations.md)(simulationsSet: [SimulationSet](../../it.unibo.alchemist.grid.simulation/-simulation-set/index.md)): [Set](https://docs.oracle.com/javase/8/docs/api/java/util/Set.html)<[RemoteResult](../../it.unibo.alchemist.grid.simulation/-remote-result/index.md)><br>Distribute and execute the simulation set on set's workers. |

//[alchemist](../../../index.md)/[it.unibo.alchemist.grid.cluster](../index.md)/[WorkerSet](index.md)

# WorkerSet

[jvm]\
interface [WorkerSet](index.md)

Set of remote nodes that can run simulations.

## Functions

| Name | Summary |
|---|---|
| [distributeSimulations](distribute-simulations.md) | [jvm]<br>abstract fun [distributeSimulations](distribute-simulations.md)(simulationsSet: [SimulationSet](../../it.unibo.alchemist.grid.simulation/-simulation-set/index.md)): [Set](https://docs.oracle.com/javase/8/docs/api/java/util/Set.html)<[RemoteResult](../../it.unibo.alchemist.grid.simulation/-remote-result/index.md)><br>Distribute and execute the simulation set on set's workers. |

## Inheritors

| Name |
|---|
| [WorkerSetImpl](../-worker-set-impl/index.md) |

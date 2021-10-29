---
title: WorkerSet
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.grid.cluster](../index.html)/[WorkerSet](index.html)



# WorkerSet



[jvm]\
interface [WorkerSet](index.html)

Set of remote nodes that can run simulations.



## Functions


| Name | Summary |
|---|---|
| [distributeSimulations](distribute-simulations.html) | [jvm]<br>abstract fun [distributeSimulations](distribute-simulations.html)(simulationsSet: [SimulationSet](../../it.unibo.alchemist.grid.simulation/-simulation-set/index.html)): [Set](https://docs.oracle.com/javase/8/docs/api/java/util/Set.html)<[RemoteResult](../../it.unibo.alchemist.grid.simulation/-remote-result/index.html)><br>Distribute and execute the simulation set on set's workers. |


## Inheritors


| Name |
|---|
| [WorkerSetImpl](../-worker-set-impl/index.html) |


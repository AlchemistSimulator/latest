---
title: WorkerSetImpl
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.grid.cluster](../index.html)/[WorkerSetImpl](index.html)



# WorkerSetImpl



[jvm]\
class [WorkerSetImpl](index.html) : [WorkerSet](../-worker-set/index.html)

Implementation of [WorkerSet](../-worker-set/index.html) which uses Apache Ignite.



## Constructors


| | |
|---|---|
| [WorkerSetImpl](-worker-set-impl.html) | [jvm]<br>open fun [WorkerSetImpl](-worker-set-impl.html)(ignite: Ignite, grp: ClusterGroup)<br>Ignite instance |


## Functions


| Name | Summary |
|---|---|
| [distributeSimulations](distribute-simulations.html) | [jvm]<br>open fun [distributeSimulations](distribute-simulations.html)(simulationsSet: [SimulationSet](../../it.unibo.alchemist.grid.simulation/-simulation-set/index.html)): [Set](https://docs.oracle.com/javase/8/docs/api/java/util/Set.html)<[RemoteResult](../../it.unibo.alchemist.grid.simulation/-remote-result/index.html)><br>Distribute and execute the simulation set on set's workers. |


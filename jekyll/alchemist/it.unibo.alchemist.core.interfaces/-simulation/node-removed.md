---
title: nodeRemoved
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.core.interfaces](../index.html)/[Simulation](index.html)/[nodeRemoved](node-removed.html)



# nodeRemoved



[jvm]\
abstract fun [nodeRemoved](node-removed.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-node/index.html)>, oldNeighborhood: [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-node/index.html)>)



This method must get called in case a node is removed from the environment during the simulation and after its neighborhood has been computed (or can be consistently computed by the simulated environment). This method provides dependency computation and is responsible of correctly removing the Node's reactions from the scheduler.



## Parameters


jvm

| | |
|---|---|
| node | the freshly removed node |
| oldNeighborhood | the neighborhood of the node as it was before it was removed (used to calculate reverse dependencies) |





---
title: nodeMoved
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.core.interfaces](../index.html)/[Simulation](index.html)/[nodeMoved](node-moved.html)



# nodeMoved



[jvm]\
abstract fun [nodeMoved](node-moved.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-node/index.html)>)



This method must get called in case a node is moved in the environment during the simulation and after its neighborhood has been computed (or can be consistently computed by the simulated environment). This method provides dependency computation and is responsible of correctly scheduling the Node's reactions.



## Parameters


jvm

| | |
|---|---|
| node | the node |





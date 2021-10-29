---
title: neighborAdded
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.core.interfaces](../index.html)/[Simulation](index.html)/[neighborAdded](neighbor-added.html)



# neighborAdded



[jvm]\
abstract fun [neighborAdded](neighbor-added.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../-scheduler/index.html)>, n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../-scheduler/index.html)>)



This method must get called in case a a communication link connecting two nodes gets created during the simulation. This method provides dependency and scheduling times re-computation for all the reactions interested by such change.



## Parameters


jvm

| | |
|---|---|
| node | the node |
| n | the second node |





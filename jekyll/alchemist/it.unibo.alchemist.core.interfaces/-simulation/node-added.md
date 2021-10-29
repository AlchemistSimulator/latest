---
title: nodeAdded
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.core.interfaces](../index.html)/[Simulation](index.html)/[nodeAdded](node-added.html)



# nodeAdded



[jvm]\
abstract fun [nodeAdded](node-added.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-node/index.html)>)



This method must get called in case a node is added to the environment during the simulation and after its neighborhood has been computed (or can be consistently computed by the simulated environment). This method provides dependency computation and is responsible of correctly scheduling the Node's new reactions.



## Parameters


jvm

| | |
|---|---|
| node | the freshly added node |



#### Throws


| | |
|---|---|
| [java.lang.IllegalMonitorStateException](https://docs.oracle.com/javase/8/docs/api/java/lang/IllegalMonitorStateException.html) | if the method gets called from a different thread than the simulation thread |




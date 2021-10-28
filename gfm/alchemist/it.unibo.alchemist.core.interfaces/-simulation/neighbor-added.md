//[alchemist](../../../index.md)/[it.unibo.alchemist.core.interfaces](../index.md)/[Simulation](index.md)/[neighborAdded](neighbor-added.md)

# neighborAdded

[jvm]\
abstract fun [neighborAdded](neighbor-added.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)>, n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)>)

This method must get called in case a a communication link connecting two nodes gets created during the simulation. This method provides dependency and scheduling times re-computation for all the reactions interested by such change.

## Parameters

jvm

| | |
|---|---|
| node | the node |
| n | the second node |

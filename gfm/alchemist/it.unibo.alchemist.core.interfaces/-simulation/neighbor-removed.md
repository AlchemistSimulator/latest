//[alchemist](../../../index.md)/[it.unibo.alchemist.core.interfaces](../index.md)/[Simulation](index.md)/[neighborRemoved](neighbor-removed.md)

# neighborRemoved

[jvm]\
abstract fun [neighborRemoved](neighbor-removed.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.interfaces/-node/index.md)>, n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.interfaces/-node/index.md)>)

This method must get called in case a a communication link connecting two nodes gets broken during the simulation. This method provides dependency and scheduling times re-computation for all the reactions interested by such change.

## Parameters

jvm

| | |
|---|---|
| node | the node |
| n | the second node |

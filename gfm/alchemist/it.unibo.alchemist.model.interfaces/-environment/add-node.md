//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Environment](index.md)/[addNode](add-node.md)

# addNode

[jvm]\
abstract fun [addNode](add-node.md)(node: [Node](../-node/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)>, p: [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md))

This method allows to add a new node to this environment. The environment is responsible to call the right method of the simulation in order to ensure that the reaction is properly scheduled.

## Parameters

jvm

| | |
|---|---|
| node | The node to add |
| p | The position where to place it |

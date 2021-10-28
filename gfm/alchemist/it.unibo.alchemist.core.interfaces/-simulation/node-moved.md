//[alchemist](../../../index.md)/[it.unibo.alchemist.core.interfaces](../index.md)/[Simulation](index.md)/[nodeMoved](node-moved.md)

# nodeMoved

[jvm]\
abstract fun [nodeMoved](node-moved.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.interfaces/-action/index.md)>)

This method must get called in case a node is moved in the environment during the simulation and after its neighborhood has been computed (or can be consistently computed by the simulated environment). This method provides dependency computation and is responsible of correctly scheduling the Node's reactions.

## Parameters

jvm

| | |
|---|---|
| node | the node |

//[alchemist](../../../index.md)/[it.unibo.alchemist.core.interfaces](../index.md)/[Simulation](index.md)/[nodeRemoved](node-removed.md)

# nodeRemoved

[jvm]\
abstract fun [nodeRemoved](node-removed.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.interfaces/-action/index.md)>, oldNeighborhood: [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.md)<[T](../../it.unibo.alchemist.model.interfaces/-action/index.md)>)

This method must get called in case a node is removed from the environment during the simulation and after its neighborhood has been computed (or can be consistently computed by the simulated environment). This method provides dependency computation and is responsible of correctly removing the Node's reactions from the scheduler.

## Parameters

jvm

| | |
|---|---|
| node | the freshly removed node |
| oldNeighborhood | the neighborhood of the node as it was before it was removed (used to calculate reverse dependencies) |

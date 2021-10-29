//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[AbstractNeighborAction](index.md)/[execute](execute.md)

# execute

[jvm]\
open fun [execute](execute.md)()

Execute the action on a random neighbor if the node has a neighborhood. Otherwise do nothing.

[jvm]\
abstract fun [execute](execute.md)(targetNode: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.reactions/-chemical-reaction/index.md)>)

Execute the action on the given target node. NOTE, it is NOT guaranteed that this method checks if the target node is in the actual neighborhood of the node.

## Parameters

jvm

| | |
|---|---|
| targetNode | the node where the action will be execute |

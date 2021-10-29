//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Reaction](index.md)/[cloneOnNewNode](clone-on-new-node.md)

# cloneOnNewNode

[jvm]\
abstract fun [cloneOnNewNode](clone-on-new-node.md)(node: [Node](../-node/index.md)<[T](../-node/index.md)>, currentTime: [Time](../-time/index.md)): [Reaction](index.md)<[T](../-node/index.md)>

This method allows to clone this reaction on a new node. It may result useful to support runtime creation of nodes with the same reaction programming, e.g. for morphogenesis.

#### Return

the cloned action

## Parameters

jvm

| | |
|---|---|
| node | The node where to clone this Reaction |
| currentTime | the time at which the clone is created (required to correctly clone the [TimeDistribution](../-time-distribution/index.md)s) |

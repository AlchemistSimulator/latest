//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Action](index.md)/[cloneAction](clone-action.md)

# cloneAction

[jvm]\
abstract fun [cloneAction](clone-action.md)(node: [Node](../-node/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)>, reaction: [Reaction](../-reaction/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)>): [Action](index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)>

This method allows to clone this action on a new node. It may result useful to support runtime creation of nodes with the same reaction programming, e.g. for morphogenesis.

#### Return

the cloned action

## Parameters

jvm

| | |
|---|---|
| node | The node where to clone this [Action](index.md) |
| reaction | The reaction to which the CURRENT action is assigned |

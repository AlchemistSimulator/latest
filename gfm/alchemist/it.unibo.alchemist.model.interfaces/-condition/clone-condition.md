//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Condition](index.md)/[cloneCondition](clone-condition.md)

# cloneCondition

[jvm]\
abstract fun [cloneCondition](clone-condition.md)(node: [Node](../-node/index.md)<[T](../-action/index.md)>, reaction: [Reaction](../-reaction/index.md)<[T](../-action/index.md)>): [Condition](index.md)<[T](../-action/index.md)>

This method allows to clone this action on a new node. It may result useful to support runtime creation of nodes with the same reaction programming, e.g. for morphogenesis.

#### Return

the cloned action

## Parameters

jvm

| | |
|---|---|
| node | The node where to clone this [Condition](index.md) |
| reaction | The [Reaction](../-reaction/index.md) where to clone this [Condition](index.md) |

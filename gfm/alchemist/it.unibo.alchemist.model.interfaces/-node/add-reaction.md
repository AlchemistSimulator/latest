//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Node](index.md)/[addReaction](add-reaction.md)

# addReaction

[jvm]\
abstract fun [addReaction](add-reaction.md)(r: [Reaction](../-reaction/index.md)<[T](../-action/index.md)>)

Adds a reaction to this node. The reaction is added only in the node, but not in the Simulation scheduler, so it will never be executed. To add the reaction also in the scheduler (and start to execute it), you have to call also the method reactionAdded.

## Parameters

jvm

| | |
|---|---|
| r | the reaction to be added |

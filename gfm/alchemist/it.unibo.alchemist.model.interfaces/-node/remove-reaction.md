//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Node](index.md)/[removeReaction](remove-reaction.md)

# removeReaction

[jvm]\
abstract fun [removeReaction](remove-reaction.md)(r: [Reaction](../-reaction/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)>)

Removes a reaction from this node. The reaction is removed only in the node, but not in the Simulation scheduler, so the scheduler will continue to execute the reaction. To remove the reaction also in the scheduler (and stop to execute it), you have to call also the method reactionRemoved.

## Parameters

jvm

| | |
|---|---|
| r | the reaction to be removed |

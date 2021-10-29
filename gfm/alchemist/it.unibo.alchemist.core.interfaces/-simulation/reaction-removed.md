//[alchemist](../../../index.md)/[it.unibo.alchemist.core.interfaces](../index.md)/[Simulation](index.md)/[reactionRemoved](reaction-removed.md)

# reactionRemoved

[jvm]\
abstract fun [reactionRemoved](reaction-removed.md)(reactionToRemove: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.interfaces/-node/index.md)>)

Removes a reaction during the simulation from the scheduler and stop to execute it. The reaction removal is not propagated in the [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md) entity. To do that call also the method [removeReaction](../../it.unibo.alchemist.model.interfaces/-node/remove-reaction.md).

## Parameters

jvm

| | |
|---|---|
| reactionToRemove | the reaction to remove |

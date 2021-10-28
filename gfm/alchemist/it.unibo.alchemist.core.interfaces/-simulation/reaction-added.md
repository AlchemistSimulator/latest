//[alchemist](../../../index.md)/[it.unibo.alchemist.core.interfaces](../index.md)/[Simulation](index.md)/[reactionAdded](reaction-added.md)

# reactionAdded

[jvm]\
abstract fun [reactionAdded](reaction-added.md)(reactionToAdd: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.interfaces/-action/index.md)>)

Adds a reaction during the simulation to the scheduler and start to execute it. The reaction addition is not propagated in the [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md) entity. To do that call also the method [addReaction](../../it.unibo.alchemist.model.interfaces/-node/add-reaction.md).

## Parameters

jvm

| | |
|---|---|
| reactionToAdd | the reaction to add |

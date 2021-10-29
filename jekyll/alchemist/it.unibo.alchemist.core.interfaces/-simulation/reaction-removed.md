---
title: reactionRemoved
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.core.interfaces](../index.html)/[Simulation](index.html)/[reactionRemoved](reaction-removed.html)



# reactionRemoved



[jvm]\
abstract fun [reactionRemoved](reaction-removed.html)(reactionToRemove: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-node/index.html)>)



Removes a reaction during the simulation from the scheduler and stop to execute it. The reaction removal is not propagated in the [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html) entity. To do that call also the method [removeReaction](../../it.unibo.alchemist.model.interfaces/-node/remove-reaction.html).



## Parameters


jvm

| | |
|---|---|
| reactionToRemove | the reaction to remove |





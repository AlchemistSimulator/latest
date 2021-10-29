---
title: reactionAdded
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.core.interfaces](../index.html)/[Simulation](index.html)/[reactionAdded](reaction-added.html)



# reactionAdded



[jvm]\
abstract fun [reactionAdded](reaction-added.html)(reactionToAdd: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../-scheduler/index.html)>)



Adds a reaction during the simulation to the scheduler and start to execute it. The reaction addition is not propagated in the [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html) entity. To do that call also the method [addReaction](../../it.unibo.alchemist.model.interfaces/-node/add-reaction.html).



## Parameters


jvm

| | |
|---|---|
| reactionToAdd | the reaction to add |





---
title: addReaction
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Node](index.html)/[addReaction](add-reaction.html)



# addReaction



[jvm]\
abstract fun [addReaction](add-reaction.html)(r: [Reaction](../-reaction/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>)



Adds a reaction to this node. The reaction is added only in the node, but not in the Simulation scheduler, so it will never be executed. To add the reaction also in the scheduler (and start to execute it), you have to call also the method reactionAdded.



## Parameters


jvm

| | |
|---|---|
| r | the reaction to be added |





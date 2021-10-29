---
title: removeReaction
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Node](index.html)/[removeReaction](remove-reaction.html)



# removeReaction



[jvm]\
abstract fun [removeReaction](remove-reaction.html)(r: [Reaction](../-reaction/index.html)<[T](index.html)>)



Removes a reaction from this node. The reaction is removed only in the node, but not in the Simulation scheduler, so the scheduler will continue to execute the reaction. To remove the reaction also in the scheduler (and stop to execute it), you have to call also the method reactionRemoved.



## Parameters


jvm

| | |
|---|---|
| r | the reaction to be removed |





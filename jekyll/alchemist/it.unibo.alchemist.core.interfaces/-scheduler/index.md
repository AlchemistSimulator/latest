---
title: Scheduler
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.core.interfaces](../index.html)/[Scheduler](index.html)



# Scheduler



[jvm]\
interface [Scheduler](index.html)<[T](index.html)>

The type which describes the concentration of a molecule This interface is meant to be implemented by the data structure(s) which must manage the reactions.



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Functions


| Name | Summary |
|---|---|
| [addReaction](add-reaction.html) | [jvm]<br>abstract fun [addReaction](add-reaction.html)(r: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-node/index.html)>)<br>Adds a reaction to the data structure. |
| [getNext](get-next.html) | [jvm]<br>abstract fun [getNext](get-next.html)(): [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-node/index.html)><br>Allows to access the next reaction to be executed. |
| [removeReaction](remove-reaction.html) | [jvm]<br>abstract fun [removeReaction](remove-reaction.html)(r: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-node/index.html)>)<br>Removes a reaction from the structure. |
| [updateReaction](update-reaction.html) | [jvm]<br>abstract fun [updateReaction](update-reaction.html)(r: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-node/index.html)>)<br>Notifies the structure that the reaction r has changed. |


## Inheritors


| Name |
|---|
| [ArrayIndexedPriorityQueue](../../it.unibo.alchemist.core.implementations/-array-indexed-priority-queue/index.html) |


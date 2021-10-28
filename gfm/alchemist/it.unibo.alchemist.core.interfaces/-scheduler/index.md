//[alchemist](../../../index.md)/[it.unibo.alchemist.core.interfaces](../index.md)/[Scheduler](index.md)

# Scheduler

[jvm]\
interface [Scheduler](index.md)<[T](index.md)>

The type which describes the concentration of a molecule This interface is meant to be implemented by the data structure(s) which must manage the reactions.

## Parameters

jvm

| | |
|---|---|
| <T> | concentration type |

## Functions

| Name | Summary |
|---|---|
| [addReaction](add-reaction.md) | [jvm]<br>abstract fun [addReaction](add-reaction.md)(r: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.interfaces/-action/index.md)>)<br>Adds a reaction to the data structure. |
| [getNext](get-next.md) | [jvm]<br>abstract fun [getNext](get-next.md)(): [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.interfaces/-action/index.md)><br>Allows to access the next reaction to be executed. |
| [removeReaction](remove-reaction.md) | [jvm]<br>abstract fun [removeReaction](remove-reaction.md)(r: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.interfaces/-action/index.md)>)<br>Removes a reaction from the structure. |
| [updateReaction](update-reaction.md) | [jvm]<br>abstract fun [updateReaction](update-reaction.md)(r: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.interfaces/-action/index.md)>)<br>Notifies the structure that the reaction r has changed. |

## Inheritors

| Name |
|---|
| [ArrayIndexedPriorityQueue](../../it.unibo.alchemist.core.implementations/-array-indexed-priority-queue/index.md) |

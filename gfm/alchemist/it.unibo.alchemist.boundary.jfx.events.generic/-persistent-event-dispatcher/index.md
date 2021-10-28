//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.jfx.events.generic](../index.md)/[PersistentEventDispatcher](index.md)

# PersistentEventDispatcher

[jvm]\
abstract class [PersistentEventDispatcher](index.md)<[T](index.md) : [TriggerAction](../-trigger-action/index.md), [E](index.md) : Event> : [AbstractEventDispatcher](../-abstract-event-dispatcher/index.md)<[T](index.md), [E](index.md)> 

An event dispatcher which doesn't overwrite its triggers when [set](set.md) is called on an already existing trigger.

## Constructors

| | |
|---|---|
| [PersistentEventDispatcher](-persistent-event-dispatcher.md) | [jvm]<br>fun [PersistentEventDispatcher](-persistent-event-dispatcher.md)() |

## Functions

| Name | Summary |
|---|---|
| [set](set.md) | [jvm]<br>open operator override fun [set](set.md)(trigger: [T](index.md), job: ([E](index.md)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>Adds a job to be performed whenever an event triggers the dispatcher through the [listener](index.md#-1989041411%2FProperties%2F-267951372). |

## Properties

| Name | Summary |
|---|---|
| [listener](index.md#-1989041411%2FProperties%2F-267951372) | [jvm]<br>abstract val [listener](index.md#-1989041411%2FProperties%2F-267951372): [ActionListener](../-action-listener/index.md)<[T](index.md), [E](index.md)><br>The listener bound to this dispatcher. |

## Inheritors

| Name |
|---|
| [KeyboardEventDispatcher](../../it.unibo.alchemist.boundary.jfx.events.keyboard/-keyboard-event-dispatcher/index.md) |
| [MouseEventDispatcher](../../it.unibo.alchemist.boundary.jfx.events.mouse/-mouse-event-dispatcher/index.md) |

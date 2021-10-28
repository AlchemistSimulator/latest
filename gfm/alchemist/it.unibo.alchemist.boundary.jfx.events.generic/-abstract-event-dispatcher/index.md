//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.jfx.events.generic](../index.md)/[AbstractEventDispatcher](index.md)

# AbstractEventDispatcher

[jvm]\
abstract class [AbstractEventDispatcher](index.md)<[T](index.md) : [TriggerAction](../-trigger-action/index.md), [E](index.md) : Event> : [EventDispatcher](../-event-dispatcher/index.md)<[T](index.md), [E](index.md)> 

A generic event dispatcher that implements action management.

## Constructors

| | |
|---|---|
| [AbstractEventDispatcher](-abstract-event-dispatcher.md) | [jvm]<br>fun [AbstractEventDispatcher](-abstract-event-dispatcher.md)() |

## Functions

| Name | Summary |
|---|---|
| [set](set.md) | [jvm]<br>open operator override fun [set](set.md)(trigger: [T](index.md), job: ([E](index.md)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>Adds a job to be performed whenever an event triggers the dispatcher through the [listener](index.md#-555057390%2FProperties%2F-267951372). |

## Properties

| Name | Summary |
|---|---|
| [listener](index.md#-555057390%2FProperties%2F-267951372) | [jvm]<br>abstract val [listener](index.md#-555057390%2FProperties%2F-267951372): [ActionListener](../-action-listener/index.md)<[T](index.md), [E](index.md)><br>The listener bound to this dispatcher. |

## Inheritors

| Name |
|---|
| [PersistentEventDispatcher](../-persistent-event-dispatcher/index.md) |

//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.jfx.events.generic](../index.md)/[EventDispatcher](index.md)

# EventDispatcher

[jvm]\
interface [EventDispatcher](index.md)<in [T](index.md) : [TriggerAction](../-trigger-action/index.md), [E](index.md) : Event>

An event dispatcher.

## Parameters

jvm

| | |
|---|---|
| T | the type of the action this dispatcher models |
| E | the type of event that triggers this dispatcher |

## Functions

| Name | Summary |
|---|---|
| [set](set.md) | [jvm]<br>abstract operator fun [set](set.md)(trigger: [T](index.md), job: ([E](index.md)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>Adds a job to be performed whenever an event triggers the dispatcher through the [listener](listener.md). |

## Properties

| Name | Summary |
|---|---|
| [listener](listener.md) | [jvm]<br>abstract val [listener](listener.md): [ActionListener](../-action-listener/index.md)<[T](index.md), [E](index.md)><br>The listener bound to this dispatcher. |

## Inheritors

| Name |
|---|
| [AbstractEventDispatcher](../-abstract-event-dispatcher/index.md) |

---
title: EventDispatcher
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.jfx.events.generic](../index.html)/[EventDispatcher](index.html)



# EventDispatcher



[jvm]\
interface [EventDispatcher](index.html)<in [T](index.html) : [TriggerAction](../-trigger-action/index.html), [E](index.html) : Event>

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
| [set](set.html) | [jvm]<br>abstract operator fun [set](set.html)(trigger: [T](index.html), job: ([E](index.html)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>Adds a job to be performed whenever an event triggers the dispatcher through the [listener](listener.html). |


## Properties


| Name | Summary |
|---|---|
| [listener](listener.html) | [jvm]<br>abstract val [listener](listener.html): [ActionListener](../-action-listener/index.html)<[T](index.html), [E](index.html)><br>The listener bound to this dispatcher. |


## Inheritors


| Name |
|---|
| [AbstractEventDispatcher](../-abstract-event-dispatcher/index.html) |


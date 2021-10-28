---
title: AbstractEventDispatcher
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.jfx.events.generic](../index.html)/[AbstractEventDispatcher](index.html)



# AbstractEventDispatcher



[jvm]\
abstract class [AbstractEventDispatcher](index.html)<[T](index.html) : [TriggerAction](../-trigger-action/index.html), [E](index.html) : Event> : [EventDispatcher](../-event-dispatcher/index.html)<[T](index.html), [E](index.html)> 

A generic event dispatcher that implements action management.



## Constructors


| | |
|---|---|
| [AbstractEventDispatcher](-abstract-event-dispatcher.html) | [jvm]<br>fun [AbstractEventDispatcher](-abstract-event-dispatcher.html)() |


## Functions


| Name | Summary |
|---|---|
| [set](set.html) | [jvm]<br>open operator override fun [set](set.html)(trigger: [T](index.html), job: ([E](index.html)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>Adds a job to be performed whenever an event triggers the dispatcher through the [listener](index.html#-555057390%2FProperties%2F-134779887). |


## Properties


| Name | Summary |
|---|---|
| [listener](index.html#-555057390%2FProperties%2F-134779887) | [jvm]<br>abstract val [listener](index.html#-555057390%2FProperties%2F-134779887): [ActionListener](../-action-listener/index.html)<[T](index.html), [E](index.html)><br>The listener bound to this dispatcher. |


## Inheritors


| Name |
|---|
| [PersistentEventDispatcher](../-persistent-event-dispatcher/index.html) |


---
title: PersistentEventDispatcher
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.jfx.events.generic](../index.html)/[PersistentEventDispatcher](index.html)



# PersistentEventDispatcher



[jvm]\
abstract class [PersistentEventDispatcher](index.html)<[T](index.html) : [TriggerAction](../-trigger-action/index.html), [E](index.html) : Event> : [AbstractEventDispatcher](../-abstract-event-dispatcher/index.html)<[T](index.html), [E](index.html)> 

An event dispatcher which doesn't overwrite its triggers when [set](set.html) is called on an already existing trigger.



## Constructors


| | |
|---|---|
| [PersistentEventDispatcher](-persistent-event-dispatcher.html) | [jvm]<br>fun [PersistentEventDispatcher](-persistent-event-dispatcher.html)() |


## Functions


| Name | Summary |
|---|---|
| [set](set.html) | [jvm]<br>open operator override fun [set](set.html)(trigger: [T](index.html), job: ([E](index.html)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>Adds a job to be performed whenever an event triggers the dispatcher through the [listener](index.html#-1989041411%2FProperties%2F-134779887). |


## Properties


| Name | Summary |
|---|---|
| [listener](index.html#-1989041411%2FProperties%2F-134779887) | [jvm]<br>abstract val [listener](index.html#-1989041411%2FProperties%2F-134779887): [ActionListener](../-action-listener/index.html)<[T](index.html), [E](index.html)><br>The listener bound to this dispatcher. |


## Inheritors


| Name |
|---|
| [KeyboardEventDispatcher](../../it.unibo.alchemist.boundary.jfx.events.keyboard/-keyboard-event-dispatcher/index.html) |
| [MouseEventDispatcher](../../it.unibo.alchemist.boundary.jfx.events.mouse/-mouse-event-dispatcher/index.html) |


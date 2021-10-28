---
title: MouseEventDispatcher
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.jfx.events.mouse](../index.html)/[MouseEventDispatcher](index.html)



# MouseEventDispatcher



[jvm]\
abstract class [MouseEventDispatcher](index.html) : [PersistentEventDispatcher](../../it.unibo.alchemist.boundary.jfx.events.generic/-persistent-event-dispatcher/index.html)<[MouseTriggerAction](../-mouse-trigger-action/index.html), MouseEvent> 

An event dispatcher in the context of mouse events.



## Constructors


| | |
|---|---|
| [MouseEventDispatcher](-mouse-event-dispatcher.html) | [jvm]<br>fun [MouseEventDispatcher](-mouse-event-dispatcher.html)() |


## Functions


| Name | Summary |
|---|---|
| [set](../-simple-mouse-event-dispatcher/index.html#-1172368341%2FFunctions%2F-134779887) | [jvm]<br>open operator override fun [set](../-simple-mouse-event-dispatcher/index.html#-1172368341%2FFunctions%2F-134779887)(trigger: [MouseTriggerAction](../-mouse-trigger-action/index.html), job: (event: MouseEvent) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>Adds a job to be performed whenever an event triggers the dispatcher through the [listener](../../it.unibo.alchemist.boundary.jfx.events.generic/-persistent-event-dispatcher/index.html#-1989041411%2FProperties%2F-134779887). |


## Properties


| Name | Summary |
|---|---|
| [listener](listener.html) | [jvm]<br>abstract override val [listener](listener.html): [MouseActionListener](../-mouse-action-listener/index.html)<br>The listener bound to this dispatcher. |


## Inheritors


| Name |
|---|
| [SimpleMouseEventDispatcher](../-simple-mouse-event-dispatcher/index.html) |


---
title: SimpleMouseEventDispatcher
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.jfx.events.mouse](../index.html)/[SimpleMouseEventDispatcher](index.html)



# SimpleMouseEventDispatcher



[jvm]\
open class [SimpleMouseEventDispatcher](index.html) : [MouseEventDispatcher](../-mouse-event-dispatcher/index.html)

A basic implementation of a mouse event dispatcher.



## Constructors


| | |
|---|---|
| [SimpleMouseEventDispatcher](-simple-mouse-event-dispatcher.html) | [jvm]<br>fun [SimpleMouseEventDispatcher](-simple-mouse-event-dispatcher.html)() |


## Functions


| Name | Summary |
|---|---|
| [set](index.html#-1172368341%2FFunctions%2F-134779887) | [jvm]<br>open operator override fun [set](index.html#-1172368341%2FFunctions%2F-134779887)(trigger: [MouseTriggerAction](../-mouse-trigger-action/index.html), job: (event: MouseEvent) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>Adds a job to be performed whenever an event triggers the dispatcher through the [listener](../../it.unibo.alchemist.boundary.jfx.events.generic/-persistent-event-dispatcher/index.html#-1989041411%2FProperties%2F-134779887). |


## Properties


| Name | Summary |
|---|---|
| [listener](listener.html) | [jvm]<br>open override val [listener](listener.html): [MouseActionListener](../-mouse-action-listener/index.html)<br>The listener bound to this dispatcher. |


## Inheritors


| Name |
|---|
| [DynamicMouseEventDispatcher](../-dynamic-mouse-event-dispatcher/index.html) |


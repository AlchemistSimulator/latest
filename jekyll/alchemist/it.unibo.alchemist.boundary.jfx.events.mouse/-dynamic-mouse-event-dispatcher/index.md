---
title: DynamicMouseEventDispatcher
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.jfx.events.mouse](../index.html)/[DynamicMouseEventDispatcher](index.html)



# DynamicMouseEventDispatcher



[jvm]\
open class [DynamicMouseEventDispatcher](index.html) : [SimpleMouseEventDispatcher](../-simple-mouse-event-dispatcher/index.html)

A mouse event dispatcher which can receive temporary actions to listen to which will only be triggered once. These temporary actions have a higher priority than actions set through action.



## Constructors


| | |
|---|---|
| [DynamicMouseEventDispatcher](-dynamic-mouse-event-dispatcher.html) | [jvm]<br>fun [DynamicMouseEventDispatcher](-dynamic-mouse-event-dispatcher.html)() |


## Functions


| Name | Summary |
|---|---|
| [set](../-simple-mouse-event-dispatcher/index.html#-1172368341%2FFunctions%2F-134779887) | [jvm]<br>open operator override fun [set](../-simple-mouse-event-dispatcher/index.html#-1172368341%2FFunctions%2F-134779887)(trigger: [MouseTriggerAction](../-mouse-trigger-action/index.html), job: (event: MouseEvent) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>Adds a job to be performed whenever an event triggers the dispatcher through the [listener](../../it.unibo.alchemist.boundary.jfx.events.generic/-persistent-event-dispatcher/index.html#-1989041411%2FProperties%2F-134779887). |
| [setDynamicAction](set-dynamic-action.html) | [jvm]<br>fun [setDynamicAction](set-dynamic-action.html)(trigger: [MouseTriggerAction](../-mouse-trigger-action/index.html), job: (MouseEvent) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>Set a dynamic action. |


## Properties


| Name | Summary |
|---|---|
| [listener](listener.html) | [jvm]<br>open override val [listener](listener.html): [MouseActionListener](../-mouse-action-listener/index.html)<br>The listener bound to this dispatcher. |


## Inheritors


| Name |
|---|
| [NodeBoundMouseEventDispatcher](../-node-bound-mouse-event-dispatcher/index.html) |


---
title: NodeBoundMouseEventDispatcher
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.jfx.events.mouse](../index.html)/[NodeBoundMouseEventDispatcher](index.html)



# NodeBoundMouseEventDispatcher



[jvm]\
open class [NodeBoundMouseEventDispatcher](index.html)(**node**: Node) : [DynamicMouseEventDispatcher](../-dynamic-mouse-event-dispatcher/index.html)

A mouse event dispatcher that catches mouse input from a node.



## Constructors


| | |
|---|---|
| [NodeBoundMouseEventDispatcher](-node-bound-mouse-event-dispatcher.html) | [jvm]<br>fun [NodeBoundMouseEventDispatcher](-node-bound-mouse-event-dispatcher.html)(node: Node) |


## Functions


| Name | Summary |
|---|---|
| [set](../-simple-mouse-event-dispatcher/index.html#-1172368341%2FFunctions%2F-134779887) | [jvm]<br>open operator override fun [set](../-simple-mouse-event-dispatcher/index.html#-1172368341%2FFunctions%2F-134779887)(trigger: [MouseTriggerAction](../-mouse-trigger-action/index.html), job: (event: MouseEvent) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>Adds a job to be performed whenever an event triggers the dispatcher through the [listener](../../it.unibo.alchemist.boundary.jfx.events.generic/-persistent-event-dispatcher/index.html#-1989041411%2FProperties%2F-134779887). |
| [setDynamicAction](../-dynamic-mouse-event-dispatcher/set-dynamic-action.html) | [jvm]<br>fun [setDynamicAction](../-dynamic-mouse-event-dispatcher/set-dynamic-action.html)(trigger: [MouseTriggerAction](../-mouse-trigger-action/index.html), job: (MouseEvent) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>Set a dynamic action. |


## Properties


| Name | Summary |
|---|---|
| [listener](index.html#175215865%2FProperties%2F-134779887) | [jvm]<br>open override val [listener](index.html#175215865%2FProperties%2F-134779887): [MouseActionListener](../-mouse-action-listener/index.html)<br>The listener bound to this dispatcher. |


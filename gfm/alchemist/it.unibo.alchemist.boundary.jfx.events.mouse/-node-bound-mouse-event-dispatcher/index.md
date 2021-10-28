//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.jfx.events.mouse](../index.md)/[NodeBoundMouseEventDispatcher](index.md)

# NodeBoundMouseEventDispatcher

[jvm]\
open class [NodeBoundMouseEventDispatcher](index.md)(**node**: Node) : [DynamicMouseEventDispatcher](../-dynamic-mouse-event-dispatcher/index.md)

A mouse event dispatcher that catches mouse input from a node.

## Constructors

| | |
|---|---|
| [NodeBoundMouseEventDispatcher](-node-bound-mouse-event-dispatcher.md) | [jvm]<br>fun [NodeBoundMouseEventDispatcher](-node-bound-mouse-event-dispatcher.md)(node: Node) |

## Functions

| Name | Summary |
|---|---|
| [set](../-simple-mouse-event-dispatcher/index.md#-1172368341%2FFunctions%2F-267951372) | [jvm]<br>open operator override fun [set](../-simple-mouse-event-dispatcher/index.md#-1172368341%2FFunctions%2F-267951372)(trigger: [MouseTriggerAction](../-mouse-trigger-action/index.md), job: (event: MouseEvent) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>Adds a job to be performed whenever an event triggers the dispatcher through the [listener](../../it.unibo.alchemist.boundary.jfx.events.generic/-persistent-event-dispatcher/index.md#-1989041411%2FProperties%2F-267951372). |
| [setDynamicAction](../-dynamic-mouse-event-dispatcher/set-dynamic-action.md) | [jvm]<br>fun [setDynamicAction](../-dynamic-mouse-event-dispatcher/set-dynamic-action.md)(trigger: [MouseTriggerAction](../-mouse-trigger-action/index.md), job: (MouseEvent) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>Set a dynamic action. |

## Properties

| Name | Summary |
|---|---|
| [listener](index.md#175215865%2FProperties%2F-267951372) | [jvm]<br>open override val [listener](index.md#175215865%2FProperties%2F-267951372): [MouseActionListener](../-mouse-action-listener/index.md)<br>The listener bound to this dispatcher. |

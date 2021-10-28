//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.jfx.events.mouse](../index.md)/[DynamicMouseEventDispatcher](index.md)

# DynamicMouseEventDispatcher

[jvm]\
open class [DynamicMouseEventDispatcher](index.md) : [SimpleMouseEventDispatcher](../-simple-mouse-event-dispatcher/index.md)

A mouse event dispatcher which can receive temporary actions to listen to which will only be triggered once. These temporary actions have a higher priority than actions set through action.

## Constructors

| | |
|---|---|
| [DynamicMouseEventDispatcher](-dynamic-mouse-event-dispatcher.md) | [jvm]<br>fun [DynamicMouseEventDispatcher](-dynamic-mouse-event-dispatcher.md)() |

## Functions

| Name | Summary |
|---|---|
| [set](../-simple-mouse-event-dispatcher/index.md#-1172368341%2FFunctions%2F-267951372) | [jvm]<br>open operator override fun [set](../-simple-mouse-event-dispatcher/index.md#-1172368341%2FFunctions%2F-267951372)(trigger: [MouseTriggerAction](../-mouse-trigger-action/index.md), job: (event: MouseEvent) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>Adds a job to be performed whenever an event triggers the dispatcher through the [listener](../../it.unibo.alchemist.boundary.jfx.events.generic/-persistent-event-dispatcher/index.md#-1989041411%2FProperties%2F-267951372). |
| [setDynamicAction](set-dynamic-action.md) | [jvm]<br>fun [setDynamicAction](set-dynamic-action.md)(trigger: [MouseTriggerAction](../-mouse-trigger-action/index.md), job: (MouseEvent) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>Set a dynamic action. |

## Properties

| Name | Summary |
|---|---|
| [listener](listener.md) | [jvm]<br>open override val [listener](listener.md): [MouseActionListener](../-mouse-action-listener/index.md)<br>The listener bound to this dispatcher. |

## Inheritors

| Name |
|---|
| [NodeBoundMouseEventDispatcher](../-node-bound-mouse-event-dispatcher/index.md) |

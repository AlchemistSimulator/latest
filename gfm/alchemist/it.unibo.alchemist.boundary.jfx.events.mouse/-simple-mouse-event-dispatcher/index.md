//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.jfx.events.mouse](../index.md)/[SimpleMouseEventDispatcher](index.md)

# SimpleMouseEventDispatcher

[jvm]\
open class [SimpleMouseEventDispatcher](index.md) : [MouseEventDispatcher](../-mouse-event-dispatcher/index.md)

A basic implementation of a mouse event dispatcher.

## Constructors

| | |
|---|---|
| [SimpleMouseEventDispatcher](-simple-mouse-event-dispatcher.md) | [jvm]<br>fun [SimpleMouseEventDispatcher](-simple-mouse-event-dispatcher.md)() |

## Functions

| Name | Summary |
|---|---|
| [set](index.md#-1172368341%2FFunctions%2F-267951372) | [jvm]<br>open operator override fun [set](index.md#-1172368341%2FFunctions%2F-267951372)(trigger: [MouseTriggerAction](../-mouse-trigger-action/index.md), job: (event: MouseEvent) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>Adds a job to be performed whenever an event triggers the dispatcher through the [listener](../../it.unibo.alchemist.boundary.jfx.events.generic/-persistent-event-dispatcher/index.md#-1989041411%2FProperties%2F-267951372). |

## Properties

| Name | Summary |
|---|---|
| [listener](listener.md) | [jvm]<br>open override val [listener](listener.md): [MouseActionListener](../-mouse-action-listener/index.md)<br>The listener bound to this dispatcher. |

## Inheritors

| Name |
|---|
| [DynamicMouseEventDispatcher](../-dynamic-mouse-event-dispatcher/index.md) |

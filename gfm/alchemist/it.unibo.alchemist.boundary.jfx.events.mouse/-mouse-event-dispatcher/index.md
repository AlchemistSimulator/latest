//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.jfx.events.mouse](../index.md)/[MouseEventDispatcher](index.md)

# MouseEventDispatcher

[jvm]\
abstract class [MouseEventDispatcher](index.md) : [PersistentEventDispatcher](../../it.unibo.alchemist.boundary.jfx.events.generic/-persistent-event-dispatcher/index.md)<[MouseTriggerAction](../-mouse-trigger-action/index.md), MouseEvent> 

An event dispatcher in the context of mouse events.

## Constructors

| | |
|---|---|
| [MouseEventDispatcher](-mouse-event-dispatcher.md) | [jvm]<br>fun [MouseEventDispatcher](-mouse-event-dispatcher.md)() |

## Functions

| Name | Summary |
|---|---|
| [set](../-simple-mouse-event-dispatcher/index.md#-1172368341%2FFunctions%2F-267951372) | [jvm]<br>open operator override fun [set](../-simple-mouse-event-dispatcher/index.md#-1172368341%2FFunctions%2F-267951372)(trigger: [MouseTriggerAction](../-mouse-trigger-action/index.md), job: (event: MouseEvent) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>Adds a job to be performed whenever an event triggers the dispatcher through the [listener](../../it.unibo.alchemist.boundary.jfx.events.generic/-persistent-event-dispatcher/index.md#-1989041411%2FProperties%2F-267951372). |

## Properties

| Name | Summary |
|---|---|
| [listener](listener.md) | [jvm]<br>abstract override val [listener](listener.md): [MouseActionListener](../-mouse-action-listener/index.md)<br>The listener bound to this dispatcher. |

## Inheritors

| Name |
|---|
| [SimpleMouseEventDispatcher](../-simple-mouse-event-dispatcher/index.md) |

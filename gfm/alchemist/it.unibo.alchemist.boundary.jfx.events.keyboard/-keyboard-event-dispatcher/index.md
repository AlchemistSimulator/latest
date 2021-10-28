//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.jfx.events.keyboard](../index.md)/[KeyboardEventDispatcher](index.md)

# KeyboardEventDispatcher

[jvm]\
abstract class [KeyboardEventDispatcher](index.md) : [PersistentEventDispatcher](../../it.unibo.alchemist.boundary.jfx.events.generic/-persistent-event-dispatcher/index.md)<[KeyboardTriggerAction](../-keyboard-trigger-action/index.md), KeyEvent> 

An event dispatcher in the context of a keyboard.

## Constructors

| | |
|---|---|
| [KeyboardEventDispatcher](-keyboard-event-dispatcher.md) | [jvm]<br>fun [KeyboardEventDispatcher](-keyboard-event-dispatcher.md)() |

## Functions

| Name | Summary |
|---|---|
| [isHeld](is-held.md) | [jvm]<br>abstract fun [isHeld](is-held.md)(key: KeyCode): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Returns whether a given key is being held or not at the time of the call. |
| [set](../-simple-keyboard-event-dispatcher/index.md#-1999063197%2FFunctions%2F-267951372) | [jvm]<br>open operator override fun [set](../-simple-keyboard-event-dispatcher/index.md#-1999063197%2FFunctions%2F-267951372)(trigger: [KeyboardTriggerAction](../-keyboard-trigger-action/index.md), job: (event: KeyEvent) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>Adds a job to be performed whenever an event triggers the dispatcher through the [listener](../../it.unibo.alchemist.boundary.jfx.events.generic/-persistent-event-dispatcher/index.md#-1989041411%2FProperties%2F-267951372). |

## Properties

| Name | Summary |
|---|---|
| [listener](listener.md) | [jvm]<br>abstract override val [listener](listener.md): [KeyboardActionListener](../-keyboard-action-listener/index.md)<br>The listener bound to this dispatcher. |

## Inheritors

| Name |
|---|
| [SimpleKeyboardEventDispatcher](../-simple-keyboard-event-dispatcher/index.md) |

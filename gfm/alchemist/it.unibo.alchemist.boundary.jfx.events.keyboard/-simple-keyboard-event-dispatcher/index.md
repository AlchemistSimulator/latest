//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.jfx.events.keyboard](../index.md)/[SimpleKeyboardEventDispatcher](index.md)

# SimpleKeyboardEventDispatcher

[jvm]\
open class [SimpleKeyboardEventDispatcher](index.md) : [KeyboardEventDispatcher](../-keyboard-event-dispatcher/index.md)

A basic implementation of [KeyboardEventDispatcher](../-keyboard-event-dispatcher/index.md).

## Constructors

| | |
|---|---|
| [SimpleKeyboardEventDispatcher](-simple-keyboard-event-dispatcher.md) | [jvm]<br>fun [SimpleKeyboardEventDispatcher](-simple-keyboard-event-dispatcher.md)() |

## Functions

| Name | Summary |
|---|---|
| [isHeld](is-held.md) | [jvm]<br>open override fun [isHeld](is-held.md)(key: KeyCode): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Returns whether a given key is being held or not at the time of the call. |
| [set](index.md#-1999063197%2FFunctions%2F-267951372) | [jvm]<br>open operator override fun [set](index.md#-1999063197%2FFunctions%2F-267951372)(trigger: [KeyboardTriggerAction](../-keyboard-trigger-action/index.md), job: (event: KeyEvent) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>Adds a job to be performed whenever an event triggers the dispatcher through the [listener](../../it.unibo.alchemist.boundary.jfx.events.generic/-persistent-event-dispatcher/index.md#-1989041411%2FProperties%2F-267951372). |

## Properties

| Name | Summary |
|---|---|
| [listener](listener.md) | [jvm]<br>open override val [listener](listener.md): [KeyboardActionListener](../-keyboard-action-listener/index.md)<br>The listener bound to this dispatcher. |

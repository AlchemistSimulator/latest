//[alchemist](../../index.md)/[it.unibo.alchemist.boundary.jfx.events.keyboard](index.md)

# Package it.unibo.alchemist.boundary.jfx.events.keyboard

## Types

| Name | Summary |
|---|---|
| [ActionOnKey](-action-on-key/index.md) | [jvm]<br>enum [ActionOnKey](-action-on-key/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[ActionOnKey](-action-on-key/index.md)> <br>The [TriggerAction](../it.unibo.alchemist.boundary.jfx.events.generic/-trigger-action/index.md) objects regarding key strokes. |
| [KeyboardActionListener](-keyboard-action-listener/index.md) | [jvm]<br>interface [KeyboardActionListener](-keyboard-action-listener/index.md) : [ActionListener](../it.unibo.alchemist.boundary.jfx.events.generic/-action-listener/index.md)<[KeyboardTriggerAction](-keyboard-trigger-action/index.md), KeyEvent> <br>An action listener in the context of a keyboard. |
| [KeyboardEventDispatcher](-keyboard-event-dispatcher/index.md) | [jvm]<br>abstract class [KeyboardEventDispatcher](-keyboard-event-dispatcher/index.md) : [PersistentEventDispatcher](../it.unibo.alchemist.boundary.jfx.events.generic/-persistent-event-dispatcher/index.md)<[KeyboardTriggerAction](-keyboard-trigger-action/index.md), KeyEvent> <br>An event dispatcher in the context of a keyboard. |
| [KeyboardTriggerAction](-keyboard-trigger-action/index.md) | [jvm]<br>data class [KeyboardTriggerAction](-keyboard-trigger-action/index.md)(**type**: [ActionOnKey](-action-on-key/index.md), **key**: KeyCode) : [TriggerAction](../it.unibo.alchemist.boundary.jfx.events.generic/-trigger-action/index.md)<br>The keyboard-related [TriggerAction](../it.unibo.alchemist.boundary.jfx.events.generic/-trigger-action/index.md). |
| [SimpleKeyboardEventDispatcher](-simple-keyboard-event-dispatcher/index.md) | [jvm]<br>open class [SimpleKeyboardEventDispatcher](-simple-keyboard-event-dispatcher/index.md) : [KeyboardEventDispatcher](-keyboard-event-dispatcher/index.md)<br>A basic implementation of [KeyboardEventDispatcher](-keyboard-event-dispatcher/index.md). |

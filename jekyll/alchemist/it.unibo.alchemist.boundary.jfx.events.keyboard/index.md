---
title: it.unibo.alchemist.boundary.jfx.events.keyboard
---
//[alchemist](../../index.html)/[it.unibo.alchemist.boundary.jfx.events.keyboard](index.html)



# Package it.unibo.alchemist.boundary.jfx.events.keyboard



## Types


| Name | Summary |
|---|---|
| [ActionOnKey](-action-on-key/index.html) | [jvm]<br>enum [ActionOnKey](-action-on-key/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[ActionOnKey](-action-on-key/index.html)> <br>The [TriggerAction](../it.unibo.alchemist.boundary.jfx.events.generic/-trigger-action/index.html) objects regarding key strokes. |
| [KeyboardActionListener](-keyboard-action-listener/index.html) | [jvm]<br>interface [KeyboardActionListener](-keyboard-action-listener/index.html) : [ActionListener](../it.unibo.alchemist.boundary.jfx.events.generic/-action-listener/index.html)<[KeyboardTriggerAction](-keyboard-trigger-action/index.html), KeyEvent> <br>An action listener in the context of a keyboard. |
| [KeyboardEventDispatcher](-keyboard-event-dispatcher/index.html) | [jvm]<br>abstract class [KeyboardEventDispatcher](-keyboard-event-dispatcher/index.html) : [PersistentEventDispatcher](../it.unibo.alchemist.boundary.jfx.events.generic/-persistent-event-dispatcher/index.html)<[KeyboardTriggerAction](-keyboard-trigger-action/index.html), KeyEvent> <br>An event dispatcher in the context of a keyboard. |
| [KeyboardTriggerAction](-keyboard-trigger-action/index.html) | [jvm]<br>data class [KeyboardTriggerAction](-keyboard-trigger-action/index.html)(**type**: [ActionOnKey](-action-on-key/index.html), **key**: KeyCode) : [TriggerAction](../it.unibo.alchemist.boundary.jfx.events.generic/-trigger-action/index.html)<br>The keyboard-related [TriggerAction](../it.unibo.alchemist.boundary.jfx.events.generic/-trigger-action/index.html). |
| [SimpleKeyboardEventDispatcher](-simple-keyboard-event-dispatcher/index.html) | [jvm]<br>open class [SimpleKeyboardEventDispatcher](-simple-keyboard-event-dispatcher/index.html) : [KeyboardEventDispatcher](-keyboard-event-dispatcher/index.html)<br>A basic implementation of [KeyboardEventDispatcher](-keyboard-event-dispatcher/index.html). |


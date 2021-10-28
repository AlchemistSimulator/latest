---
title: it.unibo.alchemist.boundary.jfx.events.mouse
---
//[alchemist](../../index.html)/[it.unibo.alchemist.boundary.jfx.events.mouse](index.html)



# Package it.unibo.alchemist.boundary.jfx.events.mouse



## Types


| Name | Summary |
|---|---|
| [ActionOnMouse](-action-on-mouse/index.html) | [jvm]<br>enum [ActionOnMouse](-action-on-mouse/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[ActionOnMouse](-action-on-mouse/index.html)> <br>Actions that can happen on a mouse and a certain mouse button. |
| [DynamicMouseEventDispatcher](-dynamic-mouse-event-dispatcher/index.html) | [jvm]<br>open class [DynamicMouseEventDispatcher](-dynamic-mouse-event-dispatcher/index.html) : [SimpleMouseEventDispatcher](-simple-mouse-event-dispatcher/index.html)<br>A mouse event dispatcher which can receive temporary actions to listen to which will only be triggered once. |
| [MouseActionListener](-mouse-action-listener/index.html) | [jvm]<br>interface [MouseActionListener](-mouse-action-listener/index.html) : [ActionListener](../it.unibo.alchemist.boundary.jfx.events.generic/-action-listener/index.html)<[MouseTriggerAction](-mouse-trigger-action/index.html), MouseEvent> <br>An action listener in the context of mouse events. |
| [MouseButtonTriggerAction](-mouse-button-trigger-action/index.html) | [jvm]<br>data class [MouseButtonTriggerAction](-mouse-button-trigger-action/index.html)(**type**: [ActionOnMouse](-action-on-mouse/index.html), **button**: MouseButton) : [MouseTriggerAction](-mouse-trigger-action/index.html)<br>A [MouseTriggerAction](-mouse-trigger-action/index.html) related to mouse button presses. |
| [MouseEventDispatcher](-mouse-event-dispatcher/index.html) | [jvm]<br>abstract class [MouseEventDispatcher](-mouse-event-dispatcher/index.html) : [PersistentEventDispatcher](../it.unibo.alchemist.boundary.jfx.events.generic/-persistent-event-dispatcher/index.html)<[MouseTriggerAction](-mouse-trigger-action/index.html), MouseEvent> <br>An event dispatcher in the context of mouse events. |
| [MouseMovement](-mouse-movement/index.html) | [jvm]<br>object [MouseMovement](-mouse-movement/index.html) : [MouseTriggerAction](-mouse-trigger-action/index.html)<br>Simple mouse actions. |
| [MouseTriggerAction](-mouse-trigger-action/index.html) | [jvm]<br>interface [MouseTriggerAction](-mouse-trigger-action/index.html) : [TriggerAction](../it.unibo.alchemist.boundary.jfx.events.generic/-trigger-action/index.html)<br>The [TriggerAction](../it.unibo.alchemist.boundary.jfx.events.generic/-trigger-action/index.html) regarding mouse events. |
| [NodeBoundMouseEventDispatcher](-node-bound-mouse-event-dispatcher/index.html) | [jvm]<br>open class [NodeBoundMouseEventDispatcher](-node-bound-mouse-event-dispatcher/index.html)(**node**: Node) : [DynamicMouseEventDispatcher](-dynamic-mouse-event-dispatcher/index.html)<br>A mouse event dispatcher that catches mouse input from a node. |
| [SimpleMouseEventDispatcher](-simple-mouse-event-dispatcher/index.html) | [jvm]<br>open class [SimpleMouseEventDispatcher](-simple-mouse-event-dispatcher/index.html) : [MouseEventDispatcher](-mouse-event-dispatcher/index.html)<br>A basic implementation of a mouse event dispatcher. |


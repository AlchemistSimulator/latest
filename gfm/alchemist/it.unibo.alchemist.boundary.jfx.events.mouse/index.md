//[alchemist](../../index.md)/[it.unibo.alchemist.boundary.jfx.events.mouse](index.md)

# Package it.unibo.alchemist.boundary.jfx.events.mouse

## Types

| Name | Summary |
|---|---|
| [ActionOnMouse](-action-on-mouse/index.md) | [jvm]<br>enum [ActionOnMouse](-action-on-mouse/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[ActionOnMouse](-action-on-mouse/index.md)> <br>Actions that can happen on a mouse and a certain mouse button. |
| [DynamicMouseEventDispatcher](-dynamic-mouse-event-dispatcher/index.md) | [jvm]<br>open class [DynamicMouseEventDispatcher](-dynamic-mouse-event-dispatcher/index.md) : [SimpleMouseEventDispatcher](-simple-mouse-event-dispatcher/index.md)<br>A mouse event dispatcher which can receive temporary actions to listen to which will only be triggered once. |
| [MouseActionListener](-mouse-action-listener/index.md) | [jvm]<br>interface [MouseActionListener](-mouse-action-listener/index.md) : [ActionListener](../it.unibo.alchemist.boundary.jfx.events.generic/-action-listener/index.md)<[MouseTriggerAction](-mouse-trigger-action/index.md), MouseEvent> <br>An action listener in the context of mouse events. |
| [MouseButtonTriggerAction](-mouse-button-trigger-action/index.md) | [jvm]<br>data class [MouseButtonTriggerAction](-mouse-button-trigger-action/index.md)(**type**: [ActionOnMouse](-action-on-mouse/index.md), **button**: MouseButton) : [MouseTriggerAction](-mouse-trigger-action/index.md)<br>A [MouseTriggerAction](-mouse-trigger-action/index.md) related to mouse button presses. |
| [MouseEventDispatcher](-mouse-event-dispatcher/index.md) | [jvm]<br>abstract class [MouseEventDispatcher](-mouse-event-dispatcher/index.md) : [PersistentEventDispatcher](../it.unibo.alchemist.boundary.jfx.events.generic/-persistent-event-dispatcher/index.md)<[MouseTriggerAction](-mouse-trigger-action/index.md), MouseEvent> <br>An event dispatcher in the context of mouse events. |
| [MouseMovement](-mouse-movement/index.md) | [jvm]<br>object [MouseMovement](-mouse-movement/index.md) : [MouseTriggerAction](-mouse-trigger-action/index.md)<br>Simple mouse actions. |
| [MouseTriggerAction](-mouse-trigger-action/index.md) | [jvm]<br>interface [MouseTriggerAction](-mouse-trigger-action/index.md) : [TriggerAction](../it.unibo.alchemist.boundary.jfx.events.generic/-trigger-action/index.md)<br>The [TriggerAction](../it.unibo.alchemist.boundary.jfx.events.generic/-trigger-action/index.md) regarding mouse events. |
| [NodeBoundMouseEventDispatcher](-node-bound-mouse-event-dispatcher/index.md) | [jvm]<br>open class [NodeBoundMouseEventDispatcher](-node-bound-mouse-event-dispatcher/index.md)(**node**: Node) : [DynamicMouseEventDispatcher](-dynamic-mouse-event-dispatcher/index.md)<br>A mouse event dispatcher that catches mouse input from a node. |
| [SimpleMouseEventDispatcher](-simple-mouse-event-dispatcher/index.md) | [jvm]<br>open class [SimpleMouseEventDispatcher](-simple-mouse-event-dispatcher/index.md) : [MouseEventDispatcher](-mouse-event-dispatcher/index.md)<br>A basic implementation of a mouse event dispatcher. |

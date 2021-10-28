//[alchemist](../../index.md)/[it.unibo.alchemist.boundary.jfx.events.generic](index.md)

# Package it.unibo.alchemist.boundary.jfx.events.generic

## Types

| Name | Summary |
|---|---|
| [AbstractEventDispatcher](-abstract-event-dispatcher/index.md) | [jvm]<br>abstract class [AbstractEventDispatcher](-abstract-event-dispatcher/index.md)<[T](-abstract-event-dispatcher/index.md) : [TriggerAction](-trigger-action/index.md), [E](-abstract-event-dispatcher/index.md) : Event> : [EventDispatcher](-event-dispatcher/index.md)<[T](-abstract-event-dispatcher/index.md), [E](-abstract-event-dispatcher/index.md)> <br>A generic event dispatcher that implements action management. |
| [ActionListener](-action-listener/index.md) | [jvm]<br>interface [ActionListener](-action-listener/index.md)<in [T](-action-listener/index.md) : [TriggerAction](-trigger-action/index.md), in [E](-action-listener/index.md) : Event><br>An action listener. |
| [EventDispatcher](-event-dispatcher/index.md) | [jvm]<br>interface [EventDispatcher](-event-dispatcher/index.md)<in [T](-event-dispatcher/index.md) : [TriggerAction](-trigger-action/index.md), [E](-event-dispatcher/index.md) : Event><br>An event dispatcher. |
| [PersistentEventDispatcher](-persistent-event-dispatcher/index.md) | [jvm]<br>abstract class [PersistentEventDispatcher](-persistent-event-dispatcher/index.md)<[T](-persistent-event-dispatcher/index.md) : [TriggerAction](-trigger-action/index.md), [E](-persistent-event-dispatcher/index.md) : Event> : [AbstractEventDispatcher](-abstract-event-dispatcher/index.md)<[T](-persistent-event-dispatcher/index.md), [E](-persistent-event-dispatcher/index.md)> <br>An event dispatcher which doesn't overwrite its triggers when [set](-persistent-event-dispatcher/set.md) is called on an already existing trigger. |
| [TriggerAction](-trigger-action/index.md) | [jvm]<br>interface [TriggerAction](-trigger-action/index.md)<br>The action that triggers an event dispatcher. |

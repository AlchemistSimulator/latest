---
title: it.unibo.alchemist.boundary.jfx.events.generic
---
//[alchemist](../../index.html)/[it.unibo.alchemist.boundary.jfx.events.generic](index.html)



# Package it.unibo.alchemist.boundary.jfx.events.generic



## Types


| Name | Summary |
|---|---|
| [AbstractEventDispatcher](-abstract-event-dispatcher/index.html) | [jvm]<br>abstract class [AbstractEventDispatcher](-abstract-event-dispatcher/index.html)<[T](-abstract-event-dispatcher/index.html) : [TriggerAction](-trigger-action/index.html), [E](-abstract-event-dispatcher/index.html) : Event> : [EventDispatcher](-event-dispatcher/index.html)<[T](-abstract-event-dispatcher/index.html), [E](-abstract-event-dispatcher/index.html)> <br>A generic event dispatcher that implements action management. |
| [ActionListener](-action-listener/index.html) | [jvm]<br>interface [ActionListener](-action-listener/index.html)<in [T](-action-listener/index.html) : [TriggerAction](-trigger-action/index.html), in [E](-action-listener/index.html) : Event><br>An action listener. |
| [EventDispatcher](-event-dispatcher/index.html) | [jvm]<br>interface [EventDispatcher](-event-dispatcher/index.html)<in [T](-event-dispatcher/index.html) : [TriggerAction](-trigger-action/index.html), [E](-event-dispatcher/index.html) : Event><br>An event dispatcher. |
| [PersistentEventDispatcher](-persistent-event-dispatcher/index.html) | [jvm]<br>abstract class [PersistentEventDispatcher](-persistent-event-dispatcher/index.html)<[T](-persistent-event-dispatcher/index.html) : [TriggerAction](-trigger-action/index.html), [E](-persistent-event-dispatcher/index.html) : Event> : [AbstractEventDispatcher](-abstract-event-dispatcher/index.html)<[T](-persistent-event-dispatcher/index.html), [E](-persistent-event-dispatcher/index.html)> <br>An event dispatcher which doesn't overwrite its triggers when [set](-persistent-event-dispatcher/set.html) is called on an already existing trigger. |
| [TriggerAction](-trigger-action/index.html) | [jvm]<br>interface [TriggerAction](-trigger-action/index.html)<br>The action that triggers an event dispatcher. |


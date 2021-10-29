---
title: KeyboardEventDispatcher
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.jfx.events.keyboard](../index.html)/[KeyboardEventDispatcher](index.html)



# KeyboardEventDispatcher



[jvm]\
abstract class [KeyboardEventDispatcher](index.html) : [PersistentEventDispatcher](../../it.unibo.alchemist.boundary.jfx.events.generic/-persistent-event-dispatcher/index.html)<[KeyboardTriggerAction](../-keyboard-trigger-action/index.html), KeyEvent> 

An event dispatcher in the context of a keyboard.



## Constructors


| | |
|---|---|
| [KeyboardEventDispatcher](-keyboard-event-dispatcher.html) | [jvm]<br>fun [KeyboardEventDispatcher](-keyboard-event-dispatcher.html)() |


## Functions


| Name | Summary |
|---|---|
| [isHeld](is-held.html) | [jvm]<br>abstract fun [isHeld](is-held.html)(key: KeyCode): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Returns whether a given key is being held or not at the time of the call. |
| [set](../-simple-keyboard-event-dispatcher/index.html#-1999063197%2FFunctions%2F-134779887) | [jvm]<br>open operator override fun [set](../-simple-keyboard-event-dispatcher/index.html#-1999063197%2FFunctions%2F-134779887)(trigger: [KeyboardTriggerAction](../-keyboard-trigger-action/index.html), job: (event: KeyEvent) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>Adds a job to be performed whenever an event triggers the dispatcher through the [listener](../../it.unibo.alchemist.boundary.jfx.events.generic/-persistent-event-dispatcher/index.html#-1989041411%2FProperties%2F-134779887). |


## Properties


| Name | Summary |
|---|---|
| [listener](listener.html) | [jvm]<br>abstract override val [listener](listener.html): [KeyboardActionListener](../-keyboard-action-listener/index.html)<br>The listener bound to this dispatcher. |


## Inheritors


| Name |
|---|
| [SimpleKeyboardEventDispatcher](../-simple-keyboard-event-dispatcher/index.html) |


---
title: SimpleKeyboardEventDispatcher
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.jfx.events.keyboard](../index.html)/[SimpleKeyboardEventDispatcher](index.html)



# SimpleKeyboardEventDispatcher



[jvm]\
open class [SimpleKeyboardEventDispatcher](index.html) : [KeyboardEventDispatcher](../-keyboard-event-dispatcher/index.html)

A basic implementation of [KeyboardEventDispatcher](../-keyboard-event-dispatcher/index.html).



## Constructors


| | |
|---|---|
| [SimpleKeyboardEventDispatcher](-simple-keyboard-event-dispatcher.html) | [jvm]<br>fun [SimpleKeyboardEventDispatcher](-simple-keyboard-event-dispatcher.html)() |


## Functions


| Name | Summary |
|---|---|
| [isHeld](is-held.html) | [jvm]<br>open override fun [isHeld](is-held.html)(key: KeyCode): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Returns whether a given key is being held or not at the time of the call. |
| [set](index.html#-1999063197%2FFunctions%2F-134779887) | [jvm]<br>open operator override fun [set](index.html#-1999063197%2FFunctions%2F-134779887)(trigger: [KeyboardTriggerAction](../-keyboard-trigger-action/index.html), job: (event: KeyEvent) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>Adds a job to be performed whenever an event triggers the dispatcher through the [listener](../../it.unibo.alchemist.boundary.jfx.events.generic/-persistent-event-dispatcher/index.html#-1989041411%2FProperties%2F-134779887). |


## Properties


| Name | Summary |
|---|---|
| [listener](listener.html) | [jvm]<br>open override val [listener](listener.html): [KeyboardActionListener](../-keyboard-action-listener/index.html)<br>The listener bound to this dispatcher. |


---
title: ActionListener
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.jfx.events.generic](../index.html)/[ActionListener](index.html)



# ActionListener



[jvm]\
interface [ActionListener](index.html)<in [T](index.html) : [TriggerAction](../-trigger-action/index.html), in [E](index.html) : Event>

An action listener.



## Parameters


jvm

| | |
|---|---|
| T | the type of triggers |
| E | the type of events that trigger the triggers |



## Functions


| Name | Summary |
|---|---|
| [action](action.html) | [jvm]<br>abstract fun [action](action.html)(action: [T](index.html), event: [E](index.html))<br>To be called whenever a certain action happens. |


## Inheritors


| Name |
|---|
| [KeyboardActionListener](../../it.unibo.alchemist.boundary.jfx.events.keyboard/-keyboard-action-listener/index.html) |
| [MouseActionListener](../../it.unibo.alchemist.boundary.jfx.events.mouse/-mouse-action-listener/index.html) |


//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.jfx.events.generic](../index.md)/[ActionListener](index.md)

# ActionListener

[jvm]\
interface [ActionListener](index.md)<in [T](index.md) : [TriggerAction](../-trigger-action/index.md), in [E](index.md) : Event>

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
| [action](action.md) | [jvm]<br>abstract fun [action](action.md)(action: [T](index.md), event: [E](index.md))<br>To be called whenever a certain action happens. |

## Inheritors

| Name |
|---|
| [KeyboardActionListener](../../it.unibo.alchemist.boundary.jfx.events.keyboard/-keyboard-action-listener/index.md) |
| [MouseActionListener](../../it.unibo.alchemist.boundary.jfx.events.mouse/-mouse-action-listener/index.md) |

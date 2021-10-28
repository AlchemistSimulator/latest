//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.interactions](../index.md)/[AnalogPanHelper](index.md)

# AnalogPanHelper

[jvm]\
class [AnalogPanHelper](index.md)(**current**: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html))

Helps manage panning done through the mouse, therefore analog in the sense that the panning can go towards any direction.

## Parameters

jvm

| | |
|---|---|
| current | the current position of the mouse. |

## Constructors

| | |
|---|---|
| [AnalogPanHelper](-analog-pan-helper.md) | [jvm]<br>fun [AnalogPanHelper](-analog-pan-helper.md)(current: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html))<br>the current position of the mouse. |

## Functions

| Name | Summary |
|---|---|
| [close](close.md) | [jvm]<br>fun [close](close.md)()<br>Closes the helper. |
| [update](update.md) | [jvm]<br>fun [update](update.md)(next: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), view: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>Updates the panning position and returns it. |

## Properties

| Name | Summary |
|---|---|
| [valid](valid.md) | [jvm]<br>var [valid](valid.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true<br>Returns whether this [AnalogPanHelper](index.md) is still valid. |

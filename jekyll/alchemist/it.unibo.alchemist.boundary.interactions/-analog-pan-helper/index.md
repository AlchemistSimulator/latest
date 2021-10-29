---
title: AnalogPanHelper
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.interactions](../index.html)/[AnalogPanHelper](index.html)



# AnalogPanHelper



[jvm]\
class [AnalogPanHelper](index.html)(**current**: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html))

Helps manage panning done through the mouse, therefore analog in the sense that the panning can go towards any direction.



## Parameters


jvm

| | |
|---|---|
| current | the current position of the mouse. |



## Constructors


| | |
|---|---|
| [AnalogPanHelper](-analog-pan-helper.html) | [jvm]<br>fun [AnalogPanHelper](-analog-pan-helper.html)(current: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html))<br>the current position of the mouse. |


## Functions


| Name | Summary |
|---|---|
| [close](close.html) | [jvm]<br>fun [close](close.html)()<br>Closes the helper. |
| [update](update.html) | [jvm]<br>fun [update](update.html)(next: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), view: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>Updates the panning position and returns it. |


## Properties


| Name | Summary |
|---|---|
| [valid](valid.html) | [jvm]<br>var [valid](valid.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true<br>Returns whether this [AnalogPanHelper](index.html) is still valid. |


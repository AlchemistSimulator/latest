---
title: AngleManager
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.wormhole.interfaces](../index.html)/[AngleManager](index.html)



# AngleManager



[jvm]\
interface [AngleManager](index.html) : [SlideInputManager](../-slide-input-manager/index.html)

A class that implements the IAngleManager interface is able to convert the sliding of any physical/virtual device/control into a positive double value that represents an angle.



## Functions


| Name | Summary |
|---|---|
| [dec](../-slide-input-manager/dec.html) | [jvm]<br>abstract fun [dec](../-slide-input-manager/dec.html)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Decreases the total amount of slides. |
| [getAngle](get-angle.html) | [jvm]<br>abstract fun [getAngle](get-angle.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Gets the angle. |
| [inc](../-slide-input-manager/inc.html) | [jvm]<br>abstract fun [inc](../-slide-input-manager/inc.html)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Increases the total amount of slides. |


## Inheritors


| Name |
|---|
| [AngleManagerImpl](../../it.unibo.alchemist.boundary.wormhole.implementation/-angle-manager-impl/index.html) |


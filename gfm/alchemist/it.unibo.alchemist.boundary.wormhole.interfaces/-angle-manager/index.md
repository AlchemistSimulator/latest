//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.wormhole.interfaces](../index.md)/[AngleManager](index.md)

# AngleManager

[jvm]\
interface [AngleManager](index.md) : [SlideInputManager](../-slide-input-manager/index.md)

A class that implements the IAngleManager interface is able to convert the sliding of any physical/virtual device/control into a positive double value that represents an angle.

## Functions

| Name | Summary |
|---|---|
| [dec](../-slide-input-manager/dec.md) | [jvm]<br>abstract fun [dec](../-slide-input-manager/dec.md)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Decreases the total amount of slides. |
| [getAngle](get-angle.md) | [jvm]<br>abstract fun [getAngle](get-angle.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Gets the angle. |
| [inc](../-slide-input-manager/inc.md) | [jvm]<br>abstract fun [inc](../-slide-input-manager/inc.md)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Increases the total amount of slides. |

## Inheritors

| Name |
|---|
| [AngleManagerImpl](../../it.unibo.alchemist.boundary.wormhole.implementation/-angle-manager-impl/index.md) |

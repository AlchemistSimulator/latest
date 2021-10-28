//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.wormhole.interfaces](../index.md)/[SlideInputManager](index.md)

# SlideInputManager

[jvm]\
interface [SlideInputManager](index.md)

ISlideInputManager is the base type for any class whose aim is to handle the the sliding of any physical/virtual device/control.

## Functions

| Name | Summary |
|---|---|
| [dec](dec.md) | [jvm]<br>abstract fun [dec](dec.md)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Decreases the total amount of slides. |
| [inc](inc.md) | [jvm]<br>abstract fun [inc](inc.md)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Increases the total amount of slides. |

## Inheritors

| Name |
|---|
| [AbstractSlideInputManager](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-slide-input-manager/index.md) |
| [ZoomManager](../-zoom-manager/index.md) |
| [AngleManager](../-angle-manager/index.md) |

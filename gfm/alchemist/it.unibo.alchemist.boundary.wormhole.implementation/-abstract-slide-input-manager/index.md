//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.wormhole.implementation](../index.md)/[AbstractSlideInputManager](index.md)

# AbstractSlideInputManager

[jvm]\
open class [AbstractSlideInputManager](index.md) : [SlideInputManager](../../it.unibo.alchemist.boundary.wormhole.interfaces/-slide-input-manager/index.md)

ASlideInputManager is the base class for any class whose aim is to handle the the sliding of any physical/virtual device/control.

## Constructors

| | |
|---|---|
| [AbstractSlideInputManager](-abstract-slide-input-manager.md) | [jvm]<br>open fun [AbstractSlideInputManager](-abstract-slide-input-manager.md)(initialValue: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), min: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), max: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Creates a new ASlideInputManager with the value in input. |

## Functions

| Name | Summary |
|---|---|
| [dec](dec.md) | [jvm]<br>fun [dec](dec.md)(val: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Decreases the total amount of slides. |
| [inc](inc.md) | [jvm]<br>fun [inc](inc.md)(val: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Increases the total amount of slides. |

## Inheritors

| Name |
|---|
| [AngleManagerImpl](../-angle-manager-impl/index.md) |
| [LinearZoomManager](../-linear-zoom-manager/index.md) |
| [ExponentialZoomManager](../-exponential-zoom-manager/index.md) |

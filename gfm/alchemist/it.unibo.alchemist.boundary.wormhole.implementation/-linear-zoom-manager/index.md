//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.wormhole.implementation](../index.md)/[LinearZoomManager](index.md)

# LinearZoomManager

[jvm]\
class [LinearZoomManager](index.md) : [AbstractSlideInputManager](../-abstract-slide-input-manager/index.md), [ZoomManager](../../it.unibo.alchemist.boundary.wormhole.interfaces/-zoom-manager/index.md)

A [LinearZoomManager](index.md) converts the sliding of any physical/virtual device/control into a zoom rate through a linear function. Zoom = amount of slides * rate.

## Constructors

| | |
|---|---|
| [LinearZoomManager](-linear-zoom-manager.md) | [jvm]<br>open fun [LinearZoomManager](-linear-zoom-manager.md)(z: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Same of [LinearZoomManager](-linear-zoom-manager.md) but rate is 1, and minimum and maximum are +/- [MAX_VALUE](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html#MAX_VALUE--). |
| [LinearZoomManager](-linear-zoom-manager.md) | [jvm]<br>open fun [LinearZoomManager](-linear-zoom-manager.md)(zoom: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), rate: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), min: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), max: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Initialize a new [LinearZoomManager](index.md) instance with the parameters in input. |

## Functions

| Name | Summary |
|---|---|
| [dec](../-abstract-slide-input-manager/dec.md) | [jvm]<br>fun [dec](../-abstract-slide-input-manager/dec.md)(val: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>abstract fun [dec](../../it.unibo.alchemist.boundary.wormhole.interfaces/-slide-input-manager/dec.md)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Decreases the total amount of slides. |
| [getZoom](get-zoom.md) | [jvm]<br>open fun [getZoom](get-zoom.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Gets the zoom rate. |
| [inc](../-abstract-slide-input-manager/inc.md) | [jvm]<br>fun [inc](../-abstract-slide-input-manager/inc.md)(val: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>abstract fun [inc](../../it.unibo.alchemist.boundary.wormhole.interfaces/-slide-input-manager/inc.md)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Increases the total amount of slides. |
| [setZoom](set-zoom.md) | [jvm]<br>open fun [setZoom](set-zoom.md)(z: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Sets the zoom rate. |

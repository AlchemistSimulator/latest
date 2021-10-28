//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.wormhole.interfaces](../index.md)/[ZoomManager](index.md)

# ZoomManager

[jvm]\
interface [ZoomManager](index.md) : [SlideInputManager](../-slide-input-manager/index.md)

A class that implements the IZoomManager interface is able to convert the sliding of any physical/virtual device/control into a positive double value that represents a zoom rate.

## Functions

| Name | Summary |
|---|---|
| [dec](../-slide-input-manager/dec.md) | [jvm]<br>abstract fun [dec](../-slide-input-manager/dec.md)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Decreases the total amount of slides. |
| [getZoom](get-zoom.md) | [jvm]<br>abstract fun [getZoom](get-zoom.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Gets the zoom rate. |
| [inc](../-slide-input-manager/inc.md) | [jvm]<br>abstract fun [inc](../-slide-input-manager/inc.md)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Increases the total amount of slides. |
| [setZoom](set-zoom.md) | [jvm]<br>abstract fun [setZoom](set-zoom.md)(rate: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Sets the zoom rate. |

## Inheritors

| Name |
|---|
| [LinearZoomManager](../../it.unibo.alchemist.boundary.wormhole.implementation/-linear-zoom-manager/index.md) |
| [ExponentialZoomManager](../../it.unibo.alchemist.boundary.wormhole.implementation/-exponential-zoom-manager/index.md) |

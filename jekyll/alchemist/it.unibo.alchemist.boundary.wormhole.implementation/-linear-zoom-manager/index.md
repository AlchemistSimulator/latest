---
title: LinearZoomManager
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.wormhole.implementation](../index.html)/[LinearZoomManager](index.html)



# LinearZoomManager



[jvm]\
class [LinearZoomManager](index.html) : [AbstractSlideInputManager](../-abstract-slide-input-manager/index.html), [ZoomManager](../../it.unibo.alchemist.boundary.wormhole.interfaces/-zoom-manager/index.html)

A [LinearZoomManager](index.html) converts the sliding of any physical/virtual device/control into a zoom rate through a linear function. Zoom = amount of slides * rate.



## Constructors


| | |
|---|---|
| [LinearZoomManager](-linear-zoom-manager.html) | [jvm]<br>open fun [LinearZoomManager](-linear-zoom-manager.html)(z: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Same of [LinearZoomManager](-linear-zoom-manager.html) but rate is 1, and minimum and maximum are +/- [MAX_VALUE](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html#MAX_VALUE--). |
| [LinearZoomManager](-linear-zoom-manager.html) | [jvm]<br>open fun [LinearZoomManager](-linear-zoom-manager.html)(zoom: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), rate: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), min: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), max: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Initialize a new [LinearZoomManager](index.html) instance with the parameters in input. |


## Functions


| Name | Summary |
|---|---|
| [dec](../-abstract-slide-input-manager/dec.html) | [jvm]<br>fun [dec](../-abstract-slide-input-manager/dec.html)(val: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>abstract fun [dec](../../it.unibo.alchemist.boundary.wormhole.interfaces/-slide-input-manager/dec.html)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Decreases the total amount of slides. |
| [getZoom](get-zoom.html) | [jvm]<br>open fun [getZoom](get-zoom.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Gets the zoom rate. |
| [inc](../-abstract-slide-input-manager/inc.html) | [jvm]<br>fun [inc](../-abstract-slide-input-manager/inc.html)(val: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>abstract fun [inc](../../it.unibo.alchemist.boundary.wormhole.interfaces/-slide-input-manager/inc.html)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Increases the total amount of slides. |
| [setZoom](set-zoom.html) | [jvm]<br>open fun [setZoom](set-zoom.html)(z: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Sets the zoom rate. |


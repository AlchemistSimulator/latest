---
title: ZoomManager
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.wormhole.interfaces](../index.html)/[ZoomManager](index.html)



# ZoomManager



[jvm]\
interface [ZoomManager](index.html) : [SlideInputManager](../-slide-input-manager/index.html)

A class that implements the IZoomManager interface is able to convert the sliding of any physical/virtual device/control into a positive double value that represents a zoom rate.



## Functions


| Name | Summary |
|---|---|
| [dec](../-slide-input-manager/dec.html) | [jvm]<br>abstract fun [dec](../-slide-input-manager/dec.html)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Decreases the total amount of slides. |
| [getZoom](get-zoom.html) | [jvm]<br>abstract fun [getZoom](get-zoom.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Gets the zoom rate. |
| [inc](../-slide-input-manager/inc.html) | [jvm]<br>abstract fun [inc](../-slide-input-manager/inc.html)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Increases the total amount of slides. |
| [setZoom](set-zoom.html) | [jvm]<br>abstract fun [setZoom](set-zoom.html)(rate: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Sets the zoom rate. |


## Inheritors


| Name |
|---|
| [LinearZoomManager](../../it.unibo.alchemist.boundary.wormhole.implementation/-linear-zoom-manager/index.html) |
| [ExponentialZoomManager](../../it.unibo.alchemist.boundary.wormhole.implementation/-exponential-zoom-manager/index.html) |


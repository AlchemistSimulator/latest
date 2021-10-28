---
title: ExponentialZoomManager
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.wormhole.implementation](../index.html)/[ExponentialZoomManager](index.html)



# ExponentialZoomManager



[jvm]\
class [ExponentialZoomManager](index.html) : [AbstractSlideInputManager](../-abstract-slide-input-manager/index.html), [ZoomManager](../../it.unibo.alchemist.boundary.wormhole.interfaces/-zoom-manager/index.html)

An ExpZoomManager converts the sliding of any physical/virtual device/control into a zoom rate through an exponential function (in this way I am sure to not see negative values ;-). Zoom = base ^ (amount of slides / normalization value).



## Constructors


| | |
|---|---|
| [ExponentialZoomManager](-exponential-zoom-manager.html) | [jvm]<br>open fun [ExponentialZoomManager](-exponential-zoom-manager.html)(z: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), b: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Same of [ExponentialZoomManager](-exponential-zoom-manager.html) but normalization value is 1. |
| [ExponentialZoomManager](-exponential-zoom-manager.html) | [jvm]<br>open fun [ExponentialZoomManager](-exponential-zoom-manager.html)(z: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), b: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), n: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Initialize a new ExpZoomManager instance with the parameters in input. |


## Functions


| Name | Summary |
|---|---|
| [dec](../-abstract-slide-input-manager/dec.html) | [jvm]<br>fun [dec](../-abstract-slide-input-manager/dec.html)(val: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>abstract fun [dec](../../it.unibo.alchemist.boundary.wormhole.interfaces/-slide-input-manager/dec.html)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Decreases the total amount of slides. |
| [getZoom](get-zoom.html) | [jvm]<br>open fun [getZoom](get-zoom.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Gets the zoom rate. |
| [inc](../-abstract-slide-input-manager/inc.html) | [jvm]<br>fun [inc](../-abstract-slide-input-manager/inc.html)(val: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>abstract fun [inc](../../it.unibo.alchemist.boundary.wormhole.interfaces/-slide-input-manager/inc.html)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Increases the total amount of slides. |
| [setZoom](set-zoom.html) | [jvm]<br>open fun [setZoom](set-zoom.html)(rate: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Sets the zoom rate. |


## Properties


| Name | Summary |
|---|---|
| [DEF_BASE](-d-e-f_-b-a-s-e.html) | [jvm]<br>val [DEF_BASE](-d-e-f_-b-a-s-e.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>DEF_BASE = "DEFault BASE". |


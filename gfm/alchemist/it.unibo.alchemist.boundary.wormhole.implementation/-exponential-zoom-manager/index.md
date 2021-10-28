//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.wormhole.implementation](../index.md)/[ExponentialZoomManager](index.md)

# ExponentialZoomManager

[jvm]\
class [ExponentialZoomManager](index.md) : [AbstractSlideInputManager](../-abstract-slide-input-manager/index.md), [ZoomManager](../../it.unibo.alchemist.boundary.wormhole.interfaces/-zoom-manager/index.md)

An ExpZoomManager converts the sliding of any physical/virtual device/control into a zoom rate through an exponential function (in this way I am sure to not see negative values ;-). Zoom = base ^ (amount of slides / normalization value).

## Constructors

| | |
|---|---|
| [ExponentialZoomManager](-exponential-zoom-manager.md) | [jvm]<br>open fun [ExponentialZoomManager](-exponential-zoom-manager.md)(z: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), b: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Same of [ExponentialZoomManager](-exponential-zoom-manager.md) but normalization value is 1. |
| [ExponentialZoomManager](-exponential-zoom-manager.md) | [jvm]<br>open fun [ExponentialZoomManager](-exponential-zoom-manager.md)(z: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), b: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), n: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Initialize a new ExpZoomManager instance with the parameters in input. |

## Functions

| Name | Summary |
|---|---|
| [dec](../-abstract-slide-input-manager/dec.md) | [jvm]<br>fun [dec](../-abstract-slide-input-manager/dec.md)(val: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>abstract fun [dec](../../it.unibo.alchemist.boundary.wormhole.interfaces/-slide-input-manager/dec.md)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Decreases the total amount of slides. |
| [getZoom](get-zoom.md) | [jvm]<br>open fun [getZoom](get-zoom.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Gets the zoom rate. |
| [inc](../-abstract-slide-input-manager/inc.md) | [jvm]<br>fun [inc](../-abstract-slide-input-manager/inc.md)(val: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>abstract fun [inc](../../it.unibo.alchemist.boundary.wormhole.interfaces/-slide-input-manager/inc.md)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Increases the total amount of slides. |
| [setZoom](set-zoom.md) | [jvm]<br>open fun [setZoom](set-zoom.md)(rate: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Sets the zoom rate. |

## Properties

| Name | Summary |
|---|---|
| [DEF_BASE](-d-e-f_-b-a-s-e.md) | [jvm]<br>val [DEF_BASE](-d-e-f_-b-a-s-e.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>DEF_BASE = "DEFault BASE". |

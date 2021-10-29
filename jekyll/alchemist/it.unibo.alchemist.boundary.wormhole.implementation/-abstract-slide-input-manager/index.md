---
title: AbstractSlideInputManager
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.wormhole.implementation](../index.html)/[AbstractSlideInputManager](index.html)



# AbstractSlideInputManager



[jvm]\
open class [AbstractSlideInputManager](index.html) : [SlideInputManager](../../it.unibo.alchemist.boundary.wormhole.interfaces/-slide-input-manager/index.html)

ASlideInputManager is the base class for any class whose aim is to handle the the sliding of any physical/virtual device/control.



## Constructors


| | |
|---|---|
| [AbstractSlideInputManager](-abstract-slide-input-manager.html) | [jvm]<br>open fun [AbstractSlideInputManager](-abstract-slide-input-manager.html)(initialValue: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), min: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), max: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Creates a new ASlideInputManager with the value in input. |


## Functions


| Name | Summary |
|---|---|
| [dec](dec.html) | [jvm]<br>fun [dec](dec.html)(val: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Decreases the total amount of slides. |
| [inc](inc.html) | [jvm]<br>fun [inc](inc.html)(val: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Increases the total amount of slides. |


## Inheritors


| Name |
|---|
| [AngleManagerImpl](../-angle-manager-impl/index.html) |
| [LinearZoomManager](../-linear-zoom-manager/index.html) |
| [ExponentialZoomManager](../-exponential-zoom-manager/index.html) |


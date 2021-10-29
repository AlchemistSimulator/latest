---
title: Euclidean2DTransformation
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d](../index.html)/[Euclidean2DTransformation](index.html)



# Euclidean2DTransformation



[jvm]\
interface [Euclidean2DTransformation](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)> 

Defines the possible transformations for a [it.unibo.alchemist.model.interfaces.geometry.GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.html) in a bidimensional euclidean space.



## Functions


| Name | Summary |
|---|---|
| [origin](index.html#368102209%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [origin](index.html#368102209%2FFunctions%2F-134779887)(position: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html))<br>[jvm]<br>open fun [origin](origin.html)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Changes origin. |
| [rotate](rotate.html) | [jvm]<br>open fun [rotate](rotate.html)(direction: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html))<br>Rotates toward the specified direction.<br>[jvm]<br>abstract fun [rotate](rotate.html)(angle: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Counter clockwise rotation. |


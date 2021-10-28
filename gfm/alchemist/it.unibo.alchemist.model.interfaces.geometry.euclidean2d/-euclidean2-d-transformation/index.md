//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d](../index.md)/[Euclidean2DTransformation](index.md)

# Euclidean2DTransformation

[jvm]\
interface [Euclidean2DTransformation](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)> 

Defines the possible transformations for a [it.unibo.alchemist.model.interfaces.geometry.GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.md) in a bidimensional euclidean space.

## Functions

| Name | Summary |
|---|---|
| [origin](index.md#368102209%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [origin](index.md#368102209%2FFunctions%2F-267951372)(position: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md))<br>[jvm]<br>open fun [origin](origin.md)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Changes origin. |
| [rotate](rotate.md) | [jvm]<br>open fun [rotate](rotate.md)(direction: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md))<br>Rotates toward the specified direction.<br>[jvm]<br>abstract fun [rotate](rotate.md)(angle: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Counter clockwise rotation. |

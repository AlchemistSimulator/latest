---
title: Euclidean2DShapeFactory
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d](../index.html)/[Euclidean2DShapeFactory](index.html)



# Euclidean2DShapeFactory



[jvm]\
interface [Euclidean2DShapeFactory](index.html) : [GeometricShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../-euclidean2-d-transformation/index.html)> 

Defines a factory of [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.html) for a bidimensional euclidean space.



## Functions


| Name | Summary |
|---|---|
| [adimensional](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/adimensional.html) | [jvm]<br>abstract fun [adimensional](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/adimensional.html)(): [AdimensionalShape](../../it.unibo.alchemist.model.implementations.geometry/-adimensional-shape/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../-euclidean2-d-transformation/index.html)><br>A special shape which does not occupy space and does not intersect with any other, not even with itself. |
| [circle](circle.html) | [jvm]<br>abstract fun [circle](circle.html)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Euclidean2DShape](../index.html#1496739300%2FClasslikes%2F-134779887)<br>A circle extends in the first and second axis by its diameter. |
| [circleSector](circle-sector.html) | [jvm]<br>abstract fun [circleSector](circle-sector.html)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), angle: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), heading: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Euclidean2DShape](../index.html#1496739300%2FClasslikes%2F-134779887)<br>A circle sector is the portion of a disk enclosed by two radii and an arc and it extends in the first and second axis by its radius and angle. |
| [rectangle](rectangle.html) | [jvm]<br>abstract fun [rectangle](rectangle.html)(width: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), height: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Euclidean2DShape](../index.html#1496739300%2FClasslikes%2F-134779887)<br>A rectangle extends in the first and second axis by its width and height. |
| [requireCompatible](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/require-compatible.html) | [jvm]<br>abstract fun [requireCompatible](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/require-compatible.html)(shape: [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.html)<*, *>): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../-euclidean2-d-transformation/index.html)><br>Requires that the given shape is compatible with the ones provided by this factory, otherwise throws an exception. |


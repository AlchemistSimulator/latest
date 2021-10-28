//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d](../index.md)/[Euclidean2DShapeFactory](index.md)

# Euclidean2DShapeFactory

[jvm]\
interface [Euclidean2DShapeFactory](index.md) : [GeometricShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), [Euclidean2DTransformation](../-euclidean2-d-transformation/index.md)> 

Defines a factory of [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.md) for a bidimensional euclidean space.

## Functions

| Name | Summary |
|---|---|
| [adimensional](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/adimensional.md) | [jvm]<br>abstract fun [adimensional](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/adimensional.md)(): [AdimensionalShape](../../it.unibo.alchemist.model.implementations.geometry/-adimensional-shape/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), [Euclidean2DTransformation](../-euclidean2-d-transformation/index.md)><br>A special shape which does not occupy space and does not intersect with any other, not even with itself. |
| [circle](circle.md) | [jvm]<br>abstract fun [circle](circle.md)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Euclidean2DShape](../index.md#1496739300%2FClasslikes%2F-267951372)<br>A circle extends in the first and second axis by its diameter. |
| [circleSector](circle-sector.md) | [jvm]<br>abstract fun [circleSector](circle-sector.md)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), angle: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), heading: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Euclidean2DShape](../index.md#1496739300%2FClasslikes%2F-267951372)<br>A circle sector is the portion of a disk enclosed by two radii and an arc and it extends in the first and second axis by its radius and angle. |
| [rectangle](rectangle.md) | [jvm]<br>abstract fun [rectangle](rectangle.md)(width: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), height: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Euclidean2DShape](../index.md#1496739300%2FClasslikes%2F-267951372)<br>A rectangle extends in the first and second axis by its width and height. |
| [requireCompatible](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/require-compatible.md) | [jvm]<br>abstract fun [requireCompatible](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/require-compatible.md)(shape: [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.md)<*, *>): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), [Euclidean2DTransformation](../-euclidean2-d-transformation/index.md)><br>Requires that the given shape is compatible with the ones provided by this factory, otherwise throws an exception. |

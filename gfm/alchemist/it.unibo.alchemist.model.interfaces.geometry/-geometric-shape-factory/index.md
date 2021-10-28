//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces.geometry](../index.md)/[GeometricShapeFactory](index.md)

# GeometricShapeFactory

[jvm]\
interface [GeometricShapeFactory](index.md)<[S](index.md) : [Vector](../-vector/index.md)<[S](index.md)>, [A](index.md) : [GeometricTransformation](../-geometric-transformation/index.md)<[S](index.md)>> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Generic factory for [GeometricShape](../-geometric-shape/index.md).

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [jvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [adimensional](adimensional.md) | [jvm]<br>abstract fun [adimensional](adimensional.md)(): [AdimensionalShape](../../it.unibo.alchemist.model.implementations.geometry/-adimensional-shape/index.md)<[S](index.md), [A](index.md)><br>A special shape which does not occupy space and does not intersect with any other, not even with itself. |
| [requireCompatible](require-compatible.md) | [jvm]<br>abstract fun [requireCompatible](require-compatible.md)(shape: [GeometricShape](../-geometric-shape/index.md)<*, *>): [GeometricShape](../-geometric-shape/index.md)<[S](index.md), [A](index.md)><br>Requires that the given shape is compatible with the ones provided by this factory, otherwise throws an exception. |

## Inheritors

| Name |
|---|
| [AbstractShapeFactory](../../it.unibo.alchemist.model.implementations.geometry/-abstract-shape-factory/index.md) |
| [Euclidean2DShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-shape-factory/index.md) |

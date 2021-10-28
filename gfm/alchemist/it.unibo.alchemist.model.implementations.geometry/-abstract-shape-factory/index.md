//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.geometry](../index.md)/[AbstractShapeFactory](index.md)

# AbstractShapeFactory

[jvm]\
abstract class [AbstractShapeFactory](index.md)<[S](index.md) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[S](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[S](index.md)>> : [GeometricShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/index.md)<[S](index.md), [A](index.md)> 

Base class for [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md) providing a standard implementation for [GeometricShapeFactory.adimensional](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/adimensional.md).

## Constructors

| | |
|---|---|
| [AbstractShapeFactory](-abstract-shape-factory.md) | [jvm]<br>fun [AbstractShapeFactory](-abstract-shape-factory.md)() |

## Functions

| Name | Summary |
|---|---|
| [adimensional](adimensional.md) | [jvm]<br>open override fun [adimensional](adimensional.md)(): [AdimensionalShape](../-adimensional-shape/index.md)<[S](index.md), [A](index.md)><br>A special shape which does not occupy space and does not intersect with any other, not even with itself. |
| [requireCompatible](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/require-compatible.md) | [jvm]<br>abstract fun [requireCompatible](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/require-compatible.md)(shape: [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.md)<*, *>): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.md)<[S](index.md), [A](index.md)><br>Requires that the given shape is compatible with the ones provided by this factory, otherwise throws an exception. |

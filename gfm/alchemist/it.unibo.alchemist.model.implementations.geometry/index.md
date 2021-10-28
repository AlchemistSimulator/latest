//[alchemist](../../index.md)/[it.unibo.alchemist.model.implementations.geometry](index.md)

# Package it.unibo.alchemist.model.implementations.geometry

## Types

| Name | Summary |
|---|---|
| [AbstractShapeFactory](-abstract-shape-factory/index.md) | [jvm]<br>abstract class [AbstractShapeFactory](-abstract-shape-factory/index.md)<[S](-abstract-shape-factory/index.md) : [Vector](../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[S](-abstract-shape-factory/index.md)>, [A](-abstract-shape-factory/index.md) : [GeometricTransformation](../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[S](-abstract-shape-factory/index.md)>> : [GeometricShapeFactory](../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/index.md)<[S](-abstract-shape-factory/index.md), [A](-abstract-shape-factory/index.md)> <br>Base class for [GeometricTransformation](../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md) providing a standard implementation for [GeometricShapeFactory.adimensional](../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/adimensional.md). |
| [AdimensionalShape](-adimensional-shape/index.md) | [jvm]<br>class [AdimensionalShape](-adimensional-shape/index.md)<[S](-adimensional-shape/index.md) : [Vector](../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[S](-adimensional-shape/index.md)>, [A](-adimensional-shape/index.md) : [GeometricTransformation](../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[S](-adimensional-shape/index.md)>>(**centroid**: [S](-adimensional-shape/index.md)) : [GeometricShape](../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.md)<[S](-adimensional-shape/index.md), [A](-adimensional-shape/index.md)> <br>A special shape which does not occupy space and does not intersect with any other, not even with itself. |
| [AwtShapeCompatible](-awt-shape-compatible/index.md) | [jvm]<br>interface [AwtShapeCompatible](-awt-shape-compatible/index.md)<br>Anything which can be represented as a [java.awt.Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html). |

---
title: it.unibo.alchemist.model.implementations.geometry
---
//[alchemist](../../index.html)/[it.unibo.alchemist.model.implementations.geometry](index.html)



# Package it.unibo.alchemist.model.implementations.geometry



## Types


| Name | Summary |
|---|---|
| [AbstractShapeFactory](-abstract-shape-factory/index.html) | [jvm]<br>abstract class [AbstractShapeFactory](-abstract-shape-factory/index.html)<[S](-abstract-shape-factory/index.html) : [Vector](../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[S](-abstract-shape-factory/index.html)>, [A](-abstract-shape-factory/index.html) : [GeometricTransformation](../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[S](-abstract-shape-factory/index.html)>> : [GeometricShapeFactory](../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/index.html)<[S](-abstract-shape-factory/index.html), [A](-abstract-shape-factory/index.html)> <br>Base class for [GeometricTransformation](../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html) providing a standard implementation for [GeometricShapeFactory.adimensional](../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/adimensional.html). |
| [AdimensionalShape](-adimensional-shape/index.html) | [jvm]<br>class [AdimensionalShape](-adimensional-shape/index.html)<[S](-adimensional-shape/index.html) : [Vector](../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[S](-adimensional-shape/index.html)>, [A](-adimensional-shape/index.html) : [GeometricTransformation](../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[S](-adimensional-shape/index.html)>>(**centroid**: [S](-adimensional-shape/index.html)) : [GeometricShape](../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.html)<[S](-adimensional-shape/index.html), [A](-adimensional-shape/index.html)> <br>A special shape which does not occupy space and does not intersect with any other, not even with itself. |
| [AwtShapeCompatible](-awt-shape-compatible/index.html) | [jvm]<br>interface [AwtShapeCompatible](-awt-shape-compatible/index.html)<br>Anything which can be represented as a [java.awt.Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html). |


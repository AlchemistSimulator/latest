---
title: AbstractShapeFactory
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.geometry](../index.html)/[AbstractShapeFactory](index.html)



# AbstractShapeFactory



[jvm]\
abstract class [AbstractShapeFactory](index.html)<[S](index.html) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[S](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[S](index.html)>> : [GeometricShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/index.html)<[S](index.html), [A](index.html)> 

Base class for [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html) providing a standard implementation for [GeometricShapeFactory.adimensional](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/adimensional.html).



## Constructors


| | |
|---|---|
| [AbstractShapeFactory](-abstract-shape-factory.html) | [jvm]<br>fun [AbstractShapeFactory](-abstract-shape-factory.html)() |


## Functions


| Name | Summary |
|---|---|
| [adimensional](adimensional.html) | [jvm]<br>open override fun [adimensional](adimensional.html)(): [AdimensionalShape](../-adimensional-shape/index.html)<[S](index.html), [A](index.html)><br>A special shape which does not occupy space and does not intersect with any other, not even with itself. |
| [requireCompatible](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/require-compatible.html) | [jvm]<br>abstract fun [requireCompatible](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/require-compatible.html)(shape: [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.html)<*, *>): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.html)<[S](index.html), [A](index.html)><br>Requires that the given shape is compatible with the ones provided by this factory, otherwise throws an exception. |


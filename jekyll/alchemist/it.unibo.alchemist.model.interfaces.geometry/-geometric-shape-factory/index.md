---
title: GeometricShapeFactory
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces.geometry](../index.html)/[GeometricShapeFactory](index.html)



# GeometricShapeFactory



[jvm]\
interface [GeometricShapeFactory](index.html)<[S](index.html) : [Vector](../-vector/index.html)<[S](index.html)>, [A](index.html) : [GeometricTransformation](../-geometric-transformation/index.html)<[S](index.html)>> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Generic factory for [GeometricShape](../-geometric-shape/index.html).



## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [adimensional](adimensional.html) | [jvm]<br>abstract fun [adimensional](adimensional.html)(): [AdimensionalShape](../../it.unibo.alchemist.model.implementations.geometry/-adimensional-shape/index.html)<[S](index.html), [A](index.html)><br>A special shape which does not occupy space and does not intersect with any other, not even with itself. |
| [requireCompatible](require-compatible.html) | [jvm]<br>abstract fun [requireCompatible](require-compatible.html)(shape: [GeometricShape](../-geometric-shape/index.html)<*, *>): [GeometricShape](../-geometric-shape/index.html)<[S](index.html), [A](index.html)><br>Requires that the given shape is compatible with the ones provided by this factory, otherwise throws an exception. |


## Inheritors


| Name |
|---|
| [AbstractShapeFactory](../../it.unibo.alchemist.model.implementations.geometry/-abstract-shape-factory/index.html) |
| [Euclidean2DShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-shape-factory/index.html) |


---
title: ConvexGeometricShape
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces.geometry](../index.html)/[ConvexGeometricShape](index.html)



# ConvexGeometricShape



[jvm]\
interface [ConvexGeometricShape](index.html)<[V](index.html) : [Vector](../-vector/index.html)<[V](index.html)>, [A](index.html) : [GeometricTransformation](../-geometric-transformation/index.html)<[V](index.html)>> : [GeometricShape](../-geometric-shape/index.html)<[V](index.html), [A](index.html)> 

A convex [GeometricShape](../-geometric-shape/index.html).



This interface models a property instead of an object, this may be unusual but consider it as a contract: interfaces are often said to be contracts the implementor has to comply, the contract defined by this interface implies convexity.



## Functions


| Name | Summary |
|---|---|
| [contains](../-geometric-shape/contains.html) | [jvm]<br>abstract fun [contains](../-geometric-shape/contains.html)(vector: [V](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [intersects](../-geometric-shape/intersects.html) | [jvm]<br>abstract fun [intersects](../-geometric-shape/intersects.html)(other: [GeometricShape](../-geometric-shape/index.html)<[V](index.html), [A](index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [transformed](../-geometric-shape/transformed.html) | [jvm]<br>abstract fun [transformed](../-geometric-shape/transformed.html)(transformation: [A](index.html).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [GeometricShape](../-geometric-shape/index.html)<[V](index.html), [A](index.html)> |


## Properties


| Name | Summary |
|---|---|
| [centroid](index.html#-1603412397%2FProperties%2F-134779887) | [jvm]<br>abstract val [centroid](index.html#-1603412397%2FProperties%2F-134779887): [V](index.html) |
| [diameter](index.html#-98529242%2FProperties%2F-134779887) | [jvm]<br>abstract val [diameter](index.html#-98529242%2FProperties%2F-134779887): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [radius](index.html#-393513663%2FProperties%2F-134779887) | [jvm]<br>open val [radius](index.html#-393513663%2FProperties%2F-134779887): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |


## Inheritors


| Name |
|---|
| [Ellipse](../../it.unibo.alchemist.model.implementations.geometry.euclidean2d/-ellipse/index.html) |
| [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html) |


---
title: GeometricShape
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces.geometry](../index.html)/[GeometricShape](index.html)



# GeometricShape



[jvm]\
interface [GeometricShape](index.html)<[S](index.html) : [Vector](../-vector/index.html)<[S](index.html)>, [A](index.html) : [GeometricTransformation](../-geometric-transformation/index.html)<[S](index.html)>> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Models a generic shape.



## Parameters


jvm

| | |
|---|---|
|  | <A> The transformations supported by the shapes in this space |



## Functions


| Name | Summary |
|---|---|
| [contains](contains.html) | [jvm]<br>abstract fun [contains](contains.html)(vector: [S](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Check if the shape contains a vector. |
| [intersects](intersects.html) | [jvm]<br>abstract fun [intersects](intersects.html)(other: [GeometricShape](index.html)<[S](index.html), [A](index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>A shape intersects another if any of its points is contained in the other one. |
| [transformed](transformed.html) | [jvm]<br>abstract fun [transformed](transformed.html)(transformation: [A](index.html).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [GeometricShape](index.html)<[S](index.html), [A](index.html)><br>Transforms the shape. |


## Properties


| Name | Summary |
|---|---|
| [centroid](centroid.html) | [jvm]<br>abstract val [centroid](centroid.html): [S](index.html)<br>The geometric center. |
| [diameter](diameter.html) | [jvm]<br>abstract val [diameter](diameter.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The largest distance between any pair of vertices. |
| [radius](radius.html) | [jvm]<br>open val [radius](radius.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Half the [diameter](diameter.html). |


## Inheritors


| Name |
|---|
| [ConvexGeometricShape](../-convex-geometric-shape/index.html) |
| [AdimensionalShape](../../it.unibo.alchemist.model.implementations.geometry/-adimensional-shape/index.html) |


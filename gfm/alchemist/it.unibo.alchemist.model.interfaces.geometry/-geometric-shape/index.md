//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces.geometry](../index.md)/[GeometricShape](index.md)

# GeometricShape

[jvm]\
interface [GeometricShape](index.md)<[S](index.md) : [Vector](../-vector/index.md)<[S](index.md)>, [A](index.md) : [GeometricTransformation](../-geometric-transformation/index.md)<[S](index.md)>> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Models a generic shape.

## Parameters

jvm

| | |
|---|---|
|  | <A> The transformations supported by the shapes in this space |

## Functions

| Name | Summary |
|---|---|
| [contains](contains.md) | [jvm]<br>abstract fun [contains](contains.md)(vector: [S](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Check if the shape contains a vector. |
| [intersects](intersects.md) | [jvm]<br>abstract fun [intersects](intersects.md)(other: [GeometricShape](index.md)<[S](index.md), [A](index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>A shape intersects another if any of its points is contained in the other one. |
| [transformed](transformed.md) | [jvm]<br>abstract fun [transformed](transformed.md)(transformation: [A](index.md).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [GeometricShape](index.md)<[S](index.md), [A](index.md)><br>Transforms the shape. |

## Properties

| Name | Summary |
|---|---|
| [centroid](centroid.md) | [jvm]<br>abstract val [centroid](centroid.md): [S](index.md)<br>The geometric center. |
| [diameter](diameter.md) | [jvm]<br>abstract val [diameter](diameter.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The largest distance between any pair of vertices. |
| [radius](radius.md) | [jvm]<br>open val [radius](radius.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Half the [diameter](diameter.md). |

## Inheritors

| Name |
|---|
| [ConvexGeometricShape](../-convex-geometric-shape/index.md) |
| [AdimensionalShape](../../it.unibo.alchemist.model.implementations.geometry/-adimensional-shape/index.md) |

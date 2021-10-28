//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces.geometry](../index.md)/[Vector](index.md)

# Vector

[jvm]\
interface [Vector](index.md)<[S](index.md) : [Vector](index.md)<[S](index.md)>>

A generic vector in a multidimensional space.

## Parameters

jvm

| | |
|---|---|
| S | self type to prevent vector operations between vectors of different spaces. |

## Functions

| Name | Summary |
|---|---|
| [angleBetween](angle-between.md) | [jvm]<br>open fun [angleBetween](angle-between.md)(other: [S](index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the angle in radians between two vectors. |
| [coerceAtLeast](coerce-at-least.md) | [jvm]<br>open fun [coerceAtLeast](coerce-at-least.md)(minimumMagnitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [S](index.md) |
| [coerceAtMost](coerce-at-most.md) | [jvm]<br>open fun [coerceAtMost](coerce-at-most.md)(maximumMagnitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [S](index.md) |
| [coerceIn](coerce-in.md) | [jvm]<br>open fun [coerceIn](coerce-in.md)(minimumMagnitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maximumMagnitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [S](index.md)<br>Performs a coercion at least and at most. |
| [distanceTo](distance-to.md) | [jvm]<br>abstract fun [distanceTo](distance-to.md)(other: [S](index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the distance between two vectors, interpreted as points in an Euclidean space. |
| [div](div.md) | [jvm]<br>open operator fun [div](div.md)(other: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [S](index.md)<br>Division by a Double. |
| [dot](dot.md) | [jvm]<br>open fun [dot](dot.md)(other: [S](index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the dot product between two vectors. |
| [get](get.md) | [jvm]<br>abstract operator fun [get](get.md)(dim: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The coordinate of this vector in the specified dimension relatively to the basis its space is described with. |
| [minus](minus.md) | [jvm]<br>abstract operator fun [minus](minus.md)(other: [S](index.md)): [S](index.md)<br>Support for subtraction. |
| [normal](normal.md) | [jvm]<br>abstract fun [normal](normal.md)(): [S](index.md)<br>Find the normal of a vector. |
| [normalized](normalized.md) | [jvm]<br>abstract fun [normalized](normalized.md)(): [S](index.md) |
| [plus](plus.md) | [jvm]<br>abstract operator fun [plus](plus.md)(other: [S](index.md)): [S](index.md)<br>Support for sum. |
| [resized](resized.md) | [jvm]<br>open fun [resized](resized.md)(newLen: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [S](index.md) |
| [times](times.md) | [jvm]<br>abstract operator fun [times](times.md)(other: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [S](index.md)<br>Multiplication by a Double. |

## Properties

| Name | Summary |
|---|---|
| [coordinates](coordinates.md) | [jvm]<br>abstract val [coordinates](coordinates.md): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)<br>Coordinates for a Cartesian space. |
| [dimensions](dimensions.md) | [jvm]<br>abstract val [dimensions](dimensions.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The dimensions of the space this vector belongs to. |
| [magnitude](magnitude.md) | [jvm]<br>open val [magnitude](magnitude.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Finds the magnitude of a vector. |

## Inheritors

| Name |
|---|
| [AbstractEuclideanPosition](../../it.unibo.alchemist.model.implementations.positions/-abstract-euclidean-position/index.md) |
| [Vector2D](../-vector2-d/index.md) |

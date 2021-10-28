//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces.geometry](../index.md)/[Vector2D](index.md)

# Vector2D

[jvm]\
interface [Vector2D](index.md)<[P](index.md) : [Vector2D](index.md)<[P](index.md)>> : [Vector](../-vector/index.md)<[P](index.md)> 

Bidimensional vector with [x](x.md) and [y](y.md) coordinates.

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [jvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [angleBetween](index.md#901441854%2FFunctions%2F-267951372) | [jvm]<br>open fun [angleBetween](index.md#901441854%2FFunctions%2F-267951372)(other: [P](index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the angle in radians between two vectors. |
| [coerceAtLeast](../-vector/coerce-at-least.md) | [jvm]<br>open fun [coerceAtLeast](../-vector/coerce-at-least.md)(minimumMagnitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](index.md) |
| [coerceAtMost](../-vector/coerce-at-most.md) | [jvm]<br>open fun [coerceAtMost](../-vector/coerce-at-most.md)(maximumMagnitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](index.md) |
| [coerceIn](../-vector/coerce-in.md) | [jvm]<br>open fun [coerceIn](../-vector/coerce-in.md)(minimumMagnitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maximumMagnitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](index.md)<br>Performs a coercion at least and at most. |
| [distanceTo](index.md#1429062915%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [distanceTo](index.md#1429062915%2FFunctions%2F-267951372)(other: [P](index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the distance between two vectors, interpreted as points in an Euclidean space. |
| [div](../-vector/div.md) | [jvm]<br>open operator fun [div](../-vector/div.md)(other: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](index.md)<br>Division by a Double. |
| [dot](dot.md) | [jvm]<br>open override fun [dot](dot.md)(other: [P](index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Dot product between bidimensional vectors. |
| [get](../-vector/get.md) | [jvm]<br>abstract operator fun [get](../-vector/get.md)(dim: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The coordinate of this vector in the specified dimension relatively to the basis its space is described with. |
| [isInRectangle](is-in-rectangle.md) | [jvm]<br>open fun [isInRectangle](is-in-rectangle.md)(origin: [Vector2D](index.md)<*>, width: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), height: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks whether the given point is inside a rectangular region described by an [origin](is-in-rectangle.md) point and [width](is-in-rectangle.md) and [height](is-in-rectangle.md) values (only positive). |
| [minus](index.md#768314559%2FFunctions%2F-267951372) | [jvm]<br>abstract operator fun [minus](index.md#768314559%2FFunctions%2F-267951372)(other: [P](index.md)): [P](index.md)<br>Support for subtraction.<br>[jvm]<br>open operator fun [minus](minus.md)(other: [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>): [P](index.md)<br>Allows subtraction with a [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html). |
| [newFrom](new-from.md) | [jvm]<br>abstract fun [newFrom](new-from.md)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](index.md)<br>Creates a new Vector2D with the same type of the current one with different [x](new-from.md) and [y](new-from.md). |
| [normal](../-vector/normal.md) | [jvm]<br>abstract fun [normal](../-vector/normal.md)(): [P](index.md)<br>Find the normal of a vector. |
| [normalized](normalized.md) | [jvm]<br>open override fun [normalized](normalized.md)(): [P](index.md)<br>Normalizes the vector. |
| [plus](index.md#-1011984263%2FFunctions%2F-267951372) | [jvm]<br>abstract operator fun [plus](index.md#-1011984263%2FFunctions%2F-267951372)(other: [P](index.md)): [P](index.md)<br>Support for sum.<br>[jvm]<br>open operator fun [plus](plus.md)(other: [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>): [P](index.md)<br>Allows summaction with a [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html). |
| [resized](../-vector/resized.md) | [jvm]<br>open fun [resized](../-vector/resized.md)(newLen: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](index.md) |
| [surrounding](surrounding.md) | [jvm]<br>open fun [surrounding](surrounding.md)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), count: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 12): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[P](index.md)><br>Creates a list of [count](surrounding.md) points equally spaced in the circle of given [radius](surrounding.md) with center in this vector. |
| [surroundingPointAt](surrounding-point-at.md) | [jvm]<br>open fun [surroundingPointAt](surrounding-point-at.md)(versor: [P](index.md), distance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](index.md)<br>Computes a point which is at a certain [distance](surrounding-point-at.md) and angle (expressed as a [versor](surrounding-point-at.md) centered in this node) from this one.<br>[jvm]<br>open fun [surroundingPointAt](surrounding-point-at.md)(angle: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), distance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](index.md)<br>Computes a point which is at a certain [distance](surrounding-point-at.md) and [angle](surrounding-point-at.md) (in radians) from this one. |
| [times](../-vector/times.md) | [jvm]<br>abstract operator fun [times](../-vector/times.md)(other: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](index.md)<br>Multiplication by a Double. |

## Properties

| Name | Summary |
|---|---|
| [asAngle](as-angle.md) | [jvm]<br>open val [asAngle](as-angle.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the angle with atan2(y, x). |
| [coordinates](index.md#301032862%2FProperties%2F-267951372) | [jvm]<br>abstract val [coordinates](index.md#301032862%2FProperties%2F-267951372): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)<br>Coordinates for a Cartesian space. |
| [dimensions](index.md#-311158380%2FProperties%2F-267951372) | [jvm]<br>abstract val [dimensions](index.md#-311158380%2FProperties%2F-267951372): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The dimensions of the space this vector belongs to. |
| [magnitude](index.md#869387817%2FProperties%2F-267951372) | [jvm]<br>open val [magnitude](index.md#869387817%2FProperties%2F-267951372): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Finds the magnitude of a vector. |
| [x](x.md) | [jvm]<br>open val [x](x.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>x coordinate. |
| [y](y.md) | [jvm]<br>open val [y](y.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>y coordinate. |

## Inheritors

| Name |
|---|
| [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md) |

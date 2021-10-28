---
title: Vector2D
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces.geometry](../index.html)/[Vector2D](index.html)



# Vector2D



[jvm]\
interface [Vector2D](index.html)<[P](index.html) : [Vector2D](index.html)<[P](index.html)>> : [Vector](../-vector/index.html)<[P](index.html)> 

Bidimensional vector with [x](x.html) and [y](y.html) coordinates.



## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [angleBetween](index.html#901441854%2FFunctions%2F-134779887) | [jvm]<br>open fun [angleBetween](index.html#901441854%2FFunctions%2F-134779887)(other: [P](index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the angle in radians between two vectors. |
| [coerceAtLeast](../-vector/coerce-at-least.html) | [jvm]<br>open fun [coerceAtLeast](../-vector/coerce-at-least.html)(minimumMagnitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](index.html) |
| [coerceAtMost](../-vector/coerce-at-most.html) | [jvm]<br>open fun [coerceAtMost](../-vector/coerce-at-most.html)(maximumMagnitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](index.html) |
| [coerceIn](../-vector/coerce-in.html) | [jvm]<br>open fun [coerceIn](../-vector/coerce-in.html)(minimumMagnitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maximumMagnitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](index.html)<br>Performs a coercion at least and at most. |
| [distanceTo](index.html#1429062915%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [distanceTo](index.html#1429062915%2FFunctions%2F-134779887)(other: [P](index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the distance between two vectors, interpreted as points in an Euclidean space. |
| [div](../-vector/div.html) | [jvm]<br>open operator fun [div](../-vector/div.html)(other: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](index.html)<br>Division by a Double. |
| [dot](dot.html) | [jvm]<br>open override fun [dot](dot.html)(other: [P](index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Dot product between bidimensional vectors. |
| [get](../-vector/get.html) | [jvm]<br>abstract operator fun [get](../-vector/get.html)(dim: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The coordinate of this vector in the specified dimension relatively to the basis its space is described with. |
| [isInRectangle](is-in-rectangle.html) | [jvm]<br>open fun [isInRectangle](is-in-rectangle.html)(origin: [Vector2D](index.html)<*>, width: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), height: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks whether the given point is inside a rectangular region described by an [origin](is-in-rectangle.html) point and [width](is-in-rectangle.html) and [height](is-in-rectangle.html) values (only positive). |
| [minus](index.html#768314559%2FFunctions%2F-134779887) | [jvm]<br>abstract operator fun [minus](index.html#768314559%2FFunctions%2F-134779887)(other: [P](index.html)): [P](index.html)<br>Support for subtraction.<br>[jvm]<br>open operator fun [minus](minus.html)(other: [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>): [P](index.html)<br>Allows subtraction with a [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html). |
| [newFrom](new-from.html) | [jvm]<br>abstract fun [newFrom](new-from.html)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](index.html)<br>Creates a new Vector2D with the same type of the current one with different [x](new-from.html) and [y](new-from.html). |
| [normal](../-vector/normal.html) | [jvm]<br>abstract fun [normal](../-vector/normal.html)(): [P](index.html)<br>Find the normal of a vector. |
| [normalized](normalized.html) | [jvm]<br>open override fun [normalized](normalized.html)(): [P](index.html)<br>Normalizes the vector. |
| [plus](index.html#-1011984263%2FFunctions%2F-134779887) | [jvm]<br>abstract operator fun [plus](index.html#-1011984263%2FFunctions%2F-134779887)(other: [P](index.html)): [P](index.html)<br>Support for sum.<br>[jvm]<br>open operator fun [plus](plus.html)(other: [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>): [P](index.html)<br>Allows summaction with a [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html). |
| [resized](../-vector/resized.html) | [jvm]<br>open fun [resized](../-vector/resized.html)(newLen: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](index.html) |
| [surrounding](surrounding.html) | [jvm]<br>open fun [surrounding](surrounding.html)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), count: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 12): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[P](index.html)><br>Creates a list of [count](surrounding.html) points equally spaced in the circle of given [radius](surrounding.html) with center in this vector. |
| [surroundingPointAt](surrounding-point-at.html) | [jvm]<br>open fun [surroundingPointAt](surrounding-point-at.html)(versor: [P](index.html), distance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](index.html)<br>Computes a point which is at a certain [distance](surrounding-point-at.html) and angle (expressed as a [versor](surrounding-point-at.html) centered in this node) from this one.<br>[jvm]<br>open fun [surroundingPointAt](surrounding-point-at.html)(angle: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), distance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](index.html)<br>Computes a point which is at a certain [distance](surrounding-point-at.html) and [angle](surrounding-point-at.html) (in radians) from this one. |
| [times](../-vector/times.html) | [jvm]<br>abstract operator fun [times](../-vector/times.html)(other: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](index.html)<br>Multiplication by a Double. |


## Properties


| Name | Summary |
|---|---|
| [asAngle](as-angle.html) | [jvm]<br>open val [asAngle](as-angle.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the angle with atan2(y, x). |
| [coordinates](index.html#301032862%2FProperties%2F-134779887) | [jvm]<br>abstract val [coordinates](index.html#301032862%2FProperties%2F-134779887): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)<br>Coordinates for a Cartesian space. |
| [dimensions](index.html#-311158380%2FProperties%2F-134779887) | [jvm]<br>abstract val [dimensions](index.html#-311158380%2FProperties%2F-134779887): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The dimensions of the space this vector belongs to. |
| [magnitude](index.html#869387817%2FProperties%2F-134779887) | [jvm]<br>open val [magnitude](index.html#869387817%2FProperties%2F-134779887): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Finds the magnitude of a vector. |
| [x](x.html) | [jvm]<br>open val [x](x.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>x coordinate. |
| [y](y.html) | [jvm]<br>open val [y](y.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>y coordinate. |


## Inheritors


| Name |
|---|
| [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html) |


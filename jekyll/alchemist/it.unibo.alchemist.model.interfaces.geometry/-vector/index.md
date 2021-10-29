---
title: Vector
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces.geometry](../index.html)/[Vector](index.html)



# Vector



[jvm]\
interface [Vector](index.html)<[S](index.html) : [Vector](index.html)<[S](index.html)>>

A generic vector in a multidimensional space.



## Parameters


jvm

| | |
|---|---|
| S | self type to prevent vector operations between vectors of different spaces. |



## Functions


| Name | Summary |
|---|---|
| [angleBetween](angle-between.html) | [jvm]<br>open fun [angleBetween](angle-between.html)(other: [S](index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the angle in radians between two vectors. |
| [coerceAtLeast](coerce-at-least.html) | [jvm]<br>open fun [coerceAtLeast](coerce-at-least.html)(minimumMagnitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [S](index.html) |
| [coerceAtMost](coerce-at-most.html) | [jvm]<br>open fun [coerceAtMost](coerce-at-most.html)(maximumMagnitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [S](index.html) |
| [coerceIn](coerce-in.html) | [jvm]<br>open fun [coerceIn](coerce-in.html)(minimumMagnitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maximumMagnitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [S](index.html)<br>Performs a coercion at least and at most. |
| [distanceTo](distance-to.html) | [jvm]<br>abstract fun [distanceTo](distance-to.html)(other: [S](index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the distance between two vectors, interpreted as points in an Euclidean space. |
| [div](div.html) | [jvm]<br>open operator fun [div](div.html)(other: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [S](index.html)<br>Division by a Double. |
| [dot](dot.html) | [jvm]<br>open fun [dot](dot.html)(other: [S](index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the dot product between two vectors. |
| [get](get.html) | [jvm]<br>abstract operator fun [get](get.html)(dim: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The coordinate of this vector in the specified dimension relatively to the basis its space is described with. |
| [minus](minus.html) | [jvm]<br>abstract operator fun [minus](minus.html)(other: [S](index.html)): [S](index.html)<br>Support for subtraction. |
| [normal](normal.html) | [jvm]<br>abstract fun [normal](normal.html)(): [S](index.html)<br>Find the normal of a vector. |
| [normalized](normalized.html) | [jvm]<br>abstract fun [normalized](normalized.html)(): [S](index.html) |
| [plus](plus.html) | [jvm]<br>abstract operator fun [plus](plus.html)(other: [S](index.html)): [S](index.html)<br>Support for sum. |
| [resized](resized.html) | [jvm]<br>open fun [resized](resized.html)(newLen: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [S](index.html) |
| [times](times.html) | [jvm]<br>abstract operator fun [times](times.html)(other: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [S](index.html)<br>Multiplication by a Double. |


## Properties


| Name | Summary |
|---|---|
| [coordinates](coordinates.html) | [jvm]<br>abstract val [coordinates](coordinates.html): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)<br>Coordinates for a Cartesian space. |
| [dimensions](dimensions.html) | [jvm]<br>abstract val [dimensions](dimensions.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The dimensions of the space this vector belongs to. |
| [magnitude](magnitude.html) | [jvm]<br>open val [magnitude](magnitude.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Finds the magnitude of a vector. |


## Inheritors


| Name |
|---|
| [AbstractEuclideanPosition](../../it.unibo.alchemist.model.implementations.positions/-abstract-euclidean-position/index.html) |
| [Vector2D](../-vector2-d/index.html) |


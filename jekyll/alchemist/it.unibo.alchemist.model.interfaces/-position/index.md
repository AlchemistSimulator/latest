---
title: Position
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Position](index.html)



# Position



[jvm]\
interface [Position](index.html)<[P](index.html) : [Position](index.html)<[P](index.html)>> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

An interface to represent a generic coordinates system.



## Parameters


jvm

| | |
|---|---|
|  | <P>     the actual {@link Position} type: this strategy allows to     progressively refine the {@link Position} by inheritance, allowing     for specifying incrementally fine grained model elements. |



## Functions


| Name | Summary |
|---|---|
| [boundingBox](bounding-box.html) | [jvm]<br>abstract fun [boundingBox](bounding-box.html)(range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[P](index.html)><br>Given a range, produces N coordinates, representing the N opposite vertices of the hypercube having the current coordinate as center and circumscribing the N-sphere defined by the range. |
| [distanceTo](distance-to.html) | [jvm]<br>abstract fun [distanceTo](distance-to.html)(otherPosition: [P](index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the distance between this position and another compatible position. |
| [getCoordinate](get-coordinate.html) | [jvm]<br>abstract fun [getCoordinate](get-coordinate.html)(dim: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Allows to access the value of a coordinate. |
| [minus](minus.html) | [jvm]<br>abstract operator fun [minus](minus.html)(other: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)): [P](index.html)<br>Considers both positions as vectors, and returns the difference between this position and the passed one. |
| [plus](plus.html) | [jvm]<br>abstract operator fun [plus](plus.html)(other: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)): [P](index.html)<br>Considers both positions as vectors, and sums them. |


## Properties


| Name | Summary |
|---|---|
| [coordinates](coordinates.html) | [jvm]<br>abstract val [coordinates](coordinates.html): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)<br>Allows to get the position as a Number array. |
| [dimensions](dimensions.html) | [jvm]<br>abstract val [dimensions](dimensions.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |


## Inheritors


| Name |
|---|
| [AbstractPosition](../../it.unibo.alchemist.model.implementations.positions/-abstract-position/index.html) |
| [Position2D](../-position2-d/index.html) |


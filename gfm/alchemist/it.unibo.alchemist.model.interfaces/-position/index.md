//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Position](index.md)

# Position

[jvm]\
interface [Position](index.md)<[P](index.md) : [Position](index.md)<[P](index.md)>> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

An interface to represent a generic coordinates system.

## Parameters

jvm

| | |
|---|---|
|  | <P>     the actual {@link Position} type: this strategy allows to     progressively refine the {@link Position} by inheritance, allowing     for specifying incrementally fine grained model elements. |

## Functions

| Name | Summary |
|---|---|
| [boundingBox](bounding-box.md) | [jvm]<br>abstract fun [boundingBox](bounding-box.md)(range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[P](index.md)><br>Given a range, produces N coordinates, representing the N opposite vertices of the hypercube having the current coordinate as center and circumscribing the N-sphere defined by the range. |
| [distanceTo](distance-to.md) | [jvm]<br>abstract fun [distanceTo](distance-to.md)(otherPosition: [P](index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the distance between this position and another compatible position. |
| [getCoordinate](get-coordinate.md) | [jvm]<br>abstract fun [getCoordinate](get-coordinate.md)(dim: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Allows to access the value of a coordinate. |
| [minus](minus.md) | [jvm]<br>abstract operator fun [minus](minus.md)(other: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)): [P](index.md)<br>Considers both positions as vectors, and returns the difference between this position and the passed one. |
| [plus](plus.md) | [jvm]<br>abstract operator fun [plus](plus.md)(other: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)): [P](index.md)<br>Considers both positions as vectors, and sums them. |

## Properties

| Name | Summary |
|---|---|
| [coordinates](coordinates.md) | [jvm]<br>abstract val [coordinates](coordinates.md): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)<br>Allows to get the position as a Number array. |
| [dimensions](dimensions.md) | [jvm]<br>abstract val [dimensions](dimensions.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

## Inheritors

| Name |
|---|
| [AbstractPosition](../../it.unibo.alchemist.model.implementations.positions/-abstract-position/index.md) |
| [Position2D](../-position2-d/index.md) |

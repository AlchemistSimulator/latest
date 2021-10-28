//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Position2D](index.md)

# Position2D

[jvm]\
interface [Position2D](index.md)<[P](index.md) : [Position2D](index.md)<[P](index.md)>> : [Position](../-position/index.md)<[P](index.md)> 

A bidimensional position.

## Parameters

jvm

| | |
|---|---|
|  | <P> </P> |

## Functions

| Name | Summary |
|---|---|
| [boundingBox](../-position/bounding-box.md) | [jvm]<br>abstract fun [boundingBox](../-position/bounding-box.md)(range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[P](index.md)><br>Given a range, produces N coordinates, representing the N opposite vertices of the hypercube having the current coordinate as center and circumscribing the N-sphere defined by the range. |
| [distanceTo](index.md#41878839%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [distanceTo](index.md#41878839%2FFunctions%2F-267951372)(otherPosition: [P](index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the distance between this position and another compatible position. |
| [getCoordinate](get-coordinate.md) | [jvm]<br>~~abstract~~ ~~override~~ ~~fun~~ [~~getCoordinate~~](get-coordinate.md)~~(~~~~dim~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~)~~~~:~~ [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Allows to access the value of a coordinate. |
| [minus](../-position/minus.md) | [jvm]<br>abstract operator fun [minus](../-position/minus.md)(other: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)): [P](index.md)<br>Considers both positions as vectors, and returns the difference between this position and the passed one. |
| [plus](../-position/plus.md) | [jvm]<br>abstract operator fun [plus](../-position/plus.md)(other: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)): [P](index.md)<br>Considers both positions as vectors, and sums them. |

## Properties

| Name | Summary |
|---|---|
| [coordinates](index.md#-1156742762%2FProperties%2F-267951372) | [jvm]<br>abstract val [coordinates](index.md#-1156742762%2FProperties%2F-267951372): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)<br>Allows to get the position as a Number array. |
| [dimensions](index.md#-219636068%2FProperties%2F-267951372) | [jvm]<br>abstract val [dimensions](index.md#-219636068%2FProperties%2F-267951372): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [x](x.md) | [jvm]<br>abstract val [x](x.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [y](y.md) | [jvm]<br>abstract val [y](y.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |

## Inheritors

| Name |
|---|
| [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md) |
| [GeoPosition](../-geo-position/index.md) |

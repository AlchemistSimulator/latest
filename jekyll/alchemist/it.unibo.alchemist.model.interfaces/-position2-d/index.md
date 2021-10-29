---
title: Position2D
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Position2D](index.html)



# Position2D



[jvm]\
interface [Position2D](index.html)<[P](index.html) : [Position2D](index.html)<[P](index.html)>> : [Position](../-position/index.html)<[P](index.html)> 

A bidimensional position.



## Parameters


jvm

| | |
|---|---|
|  | <P> </P> |



## Functions


| Name | Summary |
|---|---|
| [boundingBox](../-position/bounding-box.html) | [jvm]<br>abstract fun [boundingBox](../-position/bounding-box.html)(range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[P](index.html)><br>Given a range, produces N coordinates, representing the N opposite vertices of the hypercube having the current coordinate as center and circumscribing the N-sphere defined by the range. |
| [distanceTo](index.html#41878839%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [distanceTo](index.html#41878839%2FFunctions%2F-134779887)(otherPosition: [P](index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the distance between this position and another compatible position. |
| [getCoordinate](get-coordinate.html) | [jvm]<br>~~abstract~~ ~~override~~ ~~fun~~ [~~getCoordinate~~](get-coordinate.html)~~(~~~~dim~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~)~~~~:~~ [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Allows to access the value of a coordinate. |
| [minus](../-position/minus.html) | [jvm]<br>abstract operator fun [minus](../-position/minus.html)(other: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)): [P](index.html)<br>Considers both positions as vectors, and returns the difference between this position and the passed one. |
| [plus](../-position/plus.html) | [jvm]<br>abstract operator fun [plus](../-position/plus.html)(other: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)): [P](index.html)<br>Considers both positions as vectors, and sums them. |


## Properties


| Name | Summary |
|---|---|
| [coordinates](index.html#-1156742762%2FProperties%2F-134779887) | [jvm]<br>abstract val [coordinates](index.html#-1156742762%2FProperties%2F-134779887): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)<br>Allows to get the position as a Number array. |
| [dimensions](index.html#-219636068%2FProperties%2F-134779887) | [jvm]<br>abstract val [dimensions](index.html#-219636068%2FProperties%2F-134779887): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [x](x.html) | [jvm]<br>abstract val [x](x.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [y](y.html) | [jvm]<br>abstract val [y](y.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |


## Inheritors


| Name |
|---|
| [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html) |
| [GeoPosition](../-geo-position/index.html) |


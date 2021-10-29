//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.positions](../index.md)/[AbstractEuclideanPosition](index.md)

# AbstractEuclideanPosition

[jvm]\
abstract class [AbstractEuclideanPosition](index.md)<[P](index.md) : [AbstractEuclideanPosition](index.md)<[P](index.md)>?> : [AbstractPosition](../-abstract-position/index.md)<[P](index.md)> , [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](index.md)> 

N-dimensional Euclidean position.

## Parameters

jvm

| | |
|---|---|
| <P> | actual type |

## Functions

| Name | Summary |
|---|---|
| [angleBetween](../-euclidean2-d-position/index.md#-977094027%2FFunctions%2F-267951372) | [jvm]<br>open fun [angleBetween](../-euclidean2-d-position/index.md#-977094027%2FFunctions%2F-267951372)(other: [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [boundingBox](../-abstract-position/bounding-box.md) | [jvm]<br>fun [boundingBox](../-abstract-position/bounding-box.md)(range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[P](index.md)> |
| [coerceAtLeast](../-euclidean2-d-position/index.md#-496470145%2FFunctions%2F-267951372) | [jvm]<br>open fun [coerceAtLeast](../-euclidean2-d-position/index.md#-496470145%2FFunctions%2F-267951372)(minimumMagnitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md) |
| [coerceAtMost](../-euclidean2-d-position/index.md#499441965%2FFunctions%2F-267951372) | [jvm]<br>open fun [coerceAtMost](../-euclidean2-d-position/index.md#499441965%2FFunctions%2F-267951372)(maximumMagnitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md) |
| [coerceIn](../-euclidean2-d-position/index.md#1841783632%2FFunctions%2F-267951372) | [jvm]<br>open fun [coerceIn](../-euclidean2-d-position/index.md#1841783632%2FFunctions%2F-267951372)(minimumMagnitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maximumMagnitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md) |
| [distanceTo](../-abstract-position/distance-to.md) | [jvm]<br>fun [distanceTo](../-abstract-position/distance-to.md)(other: [P](index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [div](../-abstract-position/div.md) | [jvm]<br>fun [div](../-abstract-position/div.md)(other: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](index.md)<br>open fun [div](../-euclidean2-d-position/index.md#302170857%2FFunctions%2F-267951372)(other: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md) |
| [dot](../-euclidean2-d-position/index.md#902994349%2FFunctions%2F-267951372) | [jvm]<br>open fun [dot](../-euclidean2-d-position/index.md#902994349%2FFunctions%2F-267951372)(other: [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [equals](../-abstract-position/equals.md) | [jvm]<br>fun [equals](../-abstract-position/equals.md)(o: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [get](get.md) | [jvm]<br>fun [get](get.md)(dim: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getCoordinate](../-abstract-position/get-coordinate.md) | [jvm]<br>fun [getCoordinate](../-abstract-position/get-coordinate.md)(dim: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getCoordinates](../-abstract-position/get-coordinates.md) | [jvm]<br>fun [getCoordinates](../-abstract-position/get-coordinates.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [getDimensions](../-abstract-position/get-dimensions.md) | [jvm]<br>fun [getDimensions](../-abstract-position/get-dimensions.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMagnitude](../-euclidean2-d-position/index.md#-190619371%2FFunctions%2F-267951372) | [jvm]<br>open fun [getMagnitude](../-euclidean2-d-position/index.md#-190619371%2FFunctions%2F-267951372)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [hashCode](../-abstract-position/hash-code.md) | [jvm]<br>fun [hashCode](../-abstract-position/hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [minus](../-abstract-position/minus.md) | [jvm]<br>fun [minus](../-abstract-position/minus.md)(other: [P](index.md)): [P](index.md)<br>abstract fun [minus](../-euclidean2-d-position/index.md#935179668%2FFunctions%2F-267951372)(p: [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)): [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md) |
| [normal](../../it.unibo.alchemist.model.interfaces.geometry/-vector/normal.md) | [jvm]<br>abstract fun [normal](../../it.unibo.alchemist.model.interfaces.geometry/-vector/normal.md)(): [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md) |
| [normalized](../../it.unibo.alchemist.model.interfaces.geometry/-vector/normalized.md) | [jvm]<br>abstract fun [normalized](../../it.unibo.alchemist.model.interfaces.geometry/-vector/normalized.md)(): [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md) |
| [plus](../-abstract-position/plus.md) | [jvm]<br>fun [plus](../-abstract-position/plus.md)(other: [P](index.md)): [P](index.md)<br>abstract fun [plus](../-euclidean2-d-position/index.md#1976314394%2FFunctions%2F-267951372)(p: [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)): [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md) |
| [resized](../-euclidean2-d-position/index.md#914866794%2FFunctions%2F-267951372) | [jvm]<br>open fun [resized](../-euclidean2-d-position/index.md#914866794%2FFunctions%2F-267951372)(newLen: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md) |
| [times](../-abstract-position/times.md) | [jvm]<br>fun [times](../-abstract-position/times.md)(other: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](index.md)<br>abstract fun [times](../-euclidean2-d-position/index.md#499969556%2FFunctions%2F-267951372)(p: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md) |
| [toString](../-abstract-position/to-string.md) | [jvm]<br>open fun [toString](../-abstract-position/to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

## Inheritors

| Name |
|---|
| [Euclidean2DPosition](../-euclidean2-d-position/index.md) |

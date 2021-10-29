---
title: AbstractEuclideanPosition
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.positions](../index.html)/[AbstractEuclideanPosition](index.html)



# AbstractEuclideanPosition



[jvm]\
abstract class [AbstractEuclideanPosition](index.html)<[P](index.html) : [AbstractEuclideanPosition](index.html)<[P](index.html)>?> : [AbstractPosition](../-abstract-position/index.html)<[P](index.html)> , [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](index.html)> 

N-dimensional Euclidean position.



## Parameters


jvm

| | |
|---|---|
| <P> | actual type |



## Functions


| Name | Summary |
|---|---|
| [angleBetween](../-euclidean2-d-position/index.html#-977094027%2FFunctions%2F-134779887) | [jvm]<br>open fun [angleBetween](../-euclidean2-d-position/index.html#-977094027%2FFunctions%2F-134779887)(other: [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [boundingBox](../-abstract-position/bounding-box.html) | [jvm]<br>fun [boundingBox](../-abstract-position/bounding-box.html)(range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[P](index.html)> |
| [coerceAtLeast](../-euclidean2-d-position/index.html#-496470145%2FFunctions%2F-134779887) | [jvm]<br>open fun [coerceAtLeast](../-euclidean2-d-position/index.html#-496470145%2FFunctions%2F-134779887)(minimumMagnitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html) |
| [coerceAtMost](../-euclidean2-d-position/index.html#499441965%2FFunctions%2F-134779887) | [jvm]<br>open fun [coerceAtMost](../-euclidean2-d-position/index.html#499441965%2FFunctions%2F-134779887)(maximumMagnitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html) |
| [coerceIn](../-euclidean2-d-position/index.html#1841783632%2FFunctions%2F-134779887) | [jvm]<br>open fun [coerceIn](../-euclidean2-d-position/index.html#1841783632%2FFunctions%2F-134779887)(minimumMagnitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maximumMagnitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html) |
| [distanceTo](../-abstract-position/distance-to.html) | [jvm]<br>fun [distanceTo](../-abstract-position/distance-to.html)(other: [P](index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [div](../-abstract-position/div.html) | [jvm]<br>fun [div](../-abstract-position/div.html)(other: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](index.html)<br>open fun [div](../-euclidean2-d-position/index.html#302170857%2FFunctions%2F-134779887)(other: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html) |
| [dot](../-euclidean2-d-position/index.html#902994349%2FFunctions%2F-134779887) | [jvm]<br>open fun [dot](../-euclidean2-d-position/index.html#902994349%2FFunctions%2F-134779887)(other: [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [equals](../-abstract-position/equals.html) | [jvm]<br>fun [equals](../-abstract-position/equals.html)(o: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [get](get.html) | [jvm]<br>fun [get](get.html)(dim: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getCoordinate](../-abstract-position/get-coordinate.html) | [jvm]<br>fun [getCoordinate](../-abstract-position/get-coordinate.html)(dim: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getCoordinates](../-abstract-position/get-coordinates.html) | [jvm]<br>fun [getCoordinates](../-abstract-position/get-coordinates.html)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [getDimensions](../-abstract-position/get-dimensions.html) | [jvm]<br>fun [getDimensions](../-abstract-position/get-dimensions.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMagnitude](../-euclidean2-d-position/index.html#-190619371%2FFunctions%2F-134779887) | [jvm]<br>open fun [getMagnitude](../-euclidean2-d-position/index.html#-190619371%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [hashCode](../-abstract-position/hash-code.html) | [jvm]<br>fun [hashCode](../-abstract-position/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [minus](../-abstract-position/minus.html) | [jvm]<br>fun [minus](../-abstract-position/minus.html)(other: [P](index.html)): [P](index.html)<br>abstract fun [minus](../-euclidean2-d-position/index.html#935179668%2FFunctions%2F-134779887)(p: [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)): [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html) |
| [normal](../../it.unibo.alchemist.model.interfaces.geometry/-vector/normal.html) | [jvm]<br>abstract fun [normal](../../it.unibo.alchemist.model.interfaces.geometry/-vector/normal.html)(): [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html) |
| [normalized](../../it.unibo.alchemist.model.interfaces.geometry/-vector/normalized.html) | [jvm]<br>abstract fun [normalized](../../it.unibo.alchemist.model.interfaces.geometry/-vector/normalized.html)(): [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html) |
| [plus](../-abstract-position/plus.html) | [jvm]<br>fun [plus](../-abstract-position/plus.html)(other: [P](index.html)): [P](index.html)<br>abstract fun [plus](../-euclidean2-d-position/index.html#1976314394%2FFunctions%2F-134779887)(p: [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)): [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html) |
| [resized](../-euclidean2-d-position/index.html#914866794%2FFunctions%2F-134779887) | [jvm]<br>open fun [resized](../-euclidean2-d-position/index.html#914866794%2FFunctions%2F-134779887)(newLen: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html) |
| [times](../-abstract-position/times.html) | [jvm]<br>fun [times](../-abstract-position/times.html)(other: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](index.html)<br>abstract fun [times](../-euclidean2-d-position/index.html#499969556%2FFunctions%2F-134779887)(p: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html) |
| [toString](../-abstract-position/to-string.html) | [jvm]<br>open fun [toString](../-abstract-position/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Inheritors


| Name |
|---|
| [Euclidean2DPosition](../-euclidean2-d-position/index.html) |


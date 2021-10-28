---
title: Euclidean2DPosition
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.positions](../index.html)/[Euclidean2DPosition](index.html)



# Euclidean2DPosition



[jvm]\
class [Euclidean2DPosition](index.html) : [AbstractEuclideanPosition](../-abstract-euclidean-position/index.html)<[Euclidean2DPosition](index.html)> , [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[Euclidean2DPosition](index.html)> , [Vector2D](../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.html)<[Euclidean2DPosition](index.html)>



## Constructors


| | |
|---|---|
| [Euclidean2DPosition](-euclidean2-d-position.html) | [jvm]<br>open fun [Euclidean2DPosition](-euclidean2-d-position.html)(xp: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), yp: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>The X coordinate |
| [Euclidean2DPosition](-euclidean2-d-position.html) | [jvm]<br>open fun [Euclidean2DPosition](-euclidean2-d-position.html)(c: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>)<br>an array of length 2 containing the coordinates |


## Functions


| Name | Summary |
|---|---|
| [angleBetween](index.html#-977094027%2FFunctions%2F-134779887) | [jvm]<br>open fun [angleBetween](index.html#-977094027%2FFunctions%2F-134779887)(other: [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [boundingBox](../-abstract-position/bounding-box.html) | [jvm]<br>fun [boundingBox](../-abstract-position/bounding-box.html)(range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[P](../../it.unibo.alchemist.model.implementations.environments/-abstract2-d-environment/index.html)> |
| [coerceAtLeast](index.html#-496470145%2FFunctions%2F-134779887) | [jvm]<br>open fun [coerceAtLeast](index.html#-496470145%2FFunctions%2F-134779887)(minimumMagnitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html) |
| [coerceAtMost](index.html#499441965%2FFunctions%2F-134779887) | [jvm]<br>open fun [coerceAtMost](index.html#499441965%2FFunctions%2F-134779887)(maximumMagnitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html) |
| [coerceIn](index.html#1841783632%2FFunctions%2F-134779887) | [jvm]<br>open fun [coerceIn](index.html#1841783632%2FFunctions%2F-134779887)(minimumMagnitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maximumMagnitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html) |
| [distanceTo](../-abstract-position/distance-to.html) | [jvm]<br>fun [distanceTo](../-abstract-position/distance-to.html)(other: [P](../../it.unibo.alchemist.model.implementations.environments/-abstract2-d-environment/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [div](../-abstract-position/div.html) | [jvm]<br>fun [div](../-abstract-position/div.html)(other: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](../../it.unibo.alchemist.model.implementations.environments/-abstract2-d-environment/index.html)<br>open fun [div](index.html#302170857%2FFunctions%2F-134779887)(other: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html) |
| [dot](index.html#902994349%2FFunctions%2F-134779887) | [jvm]<br>open fun [dot](index.html#902994349%2FFunctions%2F-134779887)(other: [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [equals](../-abstract-position/equals.html) | [jvm]<br>fun [equals](../-abstract-position/equals.html)(o: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [get](../-abstract-euclidean-position/get.html) | [jvm]<br>fun [get](../-abstract-euclidean-position/get.html)(dim: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>abstract fun [get](index.html#-1903214754%2FFunctions%2F-134779887)(p: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getAsAngle](index.html#2045862806%2FFunctions%2F-134779887) | [jvm]<br>open fun [getAsAngle](index.html#2045862806%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getCoordinate](../-abstract-position/get-coordinate.html) | [jvm]<br>fun [getCoordinate](../-abstract-position/get-coordinate.html)(dim: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getCoordinates](../-abstract-position/get-coordinates.html) | [jvm]<br>fun [getCoordinates](../-abstract-position/get-coordinates.html)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [getDimensions](../-abstract-position/get-dimensions.html) | [jvm]<br>fun [getDimensions](../-abstract-position/get-dimensions.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMagnitude](index.html#-190619371%2FFunctions%2F-134779887) | [jvm]<br>open fun [getMagnitude](index.html#-190619371%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getX](get-x.html) | [jvm]<br>open fun [getX](get-x.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getY](get-y.html) | [jvm]<br>open fun [getY](get-y.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [hashCode](../-abstract-position/hash-code.html) | [jvm]<br>fun [hashCode](../-abstract-position/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isInRectangle](index.html#91972176%2FFunctions%2F-134779887) | [jvm]<br>open fun [isInRectangle](index.html#91972176%2FFunctions%2F-134779887)(origin: [Vector2D](../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, width: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), height: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [minus](../-abstract-position/minus.html) | [jvm]<br>fun [minus](../-abstract-position/minus.html)(other: [P](../../it.unibo.alchemist.model.implementations.environments/-abstract2-d-environment/index.html)): [P](../../it.unibo.alchemist.model.implementations.environments/-abstract2-d-environment/index.html)<br>abstract fun [minus](index.html#935179668%2FFunctions%2F-134779887)(p: [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)): [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html) |
| [newFrom](new-from.html) | [jvm]<br>@NotNull()<br>open fun [newFrom](new-from.html)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): @NotNull()[Euclidean2DPosition](index.html) |
| [normal](normal.html) | [jvm]<br>@NotNull()<br>open fun [normal](normal.html)(): @NotNull()[Euclidean2DPosition](index.html) |
| [normalized](../../it.unibo.alchemist.model.interfaces.geometry/-vector/normalized.html) | [jvm]<br>abstract fun [normalized](../../it.unibo.alchemist.model.interfaces.geometry/-vector/normalized.html)(): [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<br>open fun [normalized](../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/normalized.html)(): [P](../../it.unibo.alchemist.model.implementations.environments/-abstract2-d-environment/index.html) |
| [plus](../-abstract-position/plus.html) | [jvm]<br>fun [plus](../-abstract-position/plus.html)(other: [P](../../it.unibo.alchemist.model.implementations.environments/-abstract2-d-environment/index.html)): [P](../../it.unibo.alchemist.model.implementations.environments/-abstract2-d-environment/index.html)<br>abstract fun [plus](index.html#1976314394%2FFunctions%2F-134779887)(p: [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)): [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html) |
| [resized](index.html#914866794%2FFunctions%2F-134779887) | [jvm]<br>open fun [resized](index.html#914866794%2FFunctions%2F-134779887)(newLen: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html) |
| [surrounding](index.html#827351032%2FFunctions%2F-134779887) | [jvm]<br>open fun [surrounding](index.html#827351032%2FFunctions%2F-134779887)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), count: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[P](../../it.unibo.alchemist.model.implementations.environments/-abstract2-d-environment/index.html)> |
| [surroundingPointAt](index.html#963987805%2FFunctions%2F-134779887) | [jvm]<br>open fun [surroundingPointAt](index.html#963987805%2FFunctions%2F-134779887)(angle: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), distance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](../../it.unibo.alchemist.model.implementations.environments/-abstract2-d-environment/index.html) |
| [times](../-abstract-position/times.html) | [jvm]<br>fun [times](../-abstract-position/times.html)(other: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](../../it.unibo.alchemist.model.implementations.environments/-abstract2-d-environment/index.html)<br>abstract fun [times](index.html#499969556%2FFunctions%2F-134779887)(p: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [S](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html) |
| [toString](../-abstract-position/to-string.html) | [jvm]<br>open fun [toString](../-abstract-position/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


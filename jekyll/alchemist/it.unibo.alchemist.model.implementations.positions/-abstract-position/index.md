---
title: AbstractPosition
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.positions](../index.html)/[AbstractPosition](index.html)



# AbstractPosition



[jvm]\
abstract class [AbstractPosition](index.html)<[P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>?> : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)> 

N-dimensional position.



## Parameters


jvm

| | |
|---|---|
| <P> | actual type |



## Functions


| Name | Summary |
|---|---|
| [boundingBox](bounding-box.html) | [jvm]<br>fun [boundingBox](bounding-box.html)(range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)> |
| [distanceTo](distance-to.html) | [jvm]<br>fun [distanceTo](distance-to.html)(@NotNull()other: @NotNull()[P](index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [div](div.html) | [jvm]<br>@NotNull()<br>fun [div](div.html)(other: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): @NotNull()[P](index.html)<br>Division by a number. |
| [equals](equals.html) | [jvm]<br>fun [equals](equals.html)(o: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getCoordinate](get-coordinate.html) | [jvm]<br>fun [getCoordinate](get-coordinate.html)(dim: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getCoordinates](get-coordinates.html) | [jvm]<br>@NotNull()<br>fun [getCoordinates](get-coordinates.html)(): @NotNull()[Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [getDimensions](get-dimensions.html) | [jvm]<br>fun [getDimensions](get-dimensions.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [hashCode](hash-code.html) | [jvm]<br>fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [minus](minus.html) | [jvm]<br>@NotNull()<br>fun [minus](minus.html)(@NotNull()other: @NotNull()[P](index.html)): @NotNull()[P](index.html)<br>Same as [minus](minus.html), with the internal representation of other.<br>[jvm]<br>@NotNull()<br>fun [minus](minus.html)(@NotNull()other: @NotNull()[Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>): @NotNull()[P](index.html) |
| [plus](plus.html) | [jvm]<br>@NotNull()<br>fun [plus](plus.html)(@NotNull()other: @NotNull()[P](index.html)): @NotNull()[P](index.html)<br>Same as [plus](plus.html), with the internal representation of other.<br>[jvm]<br>@NotNull()<br>fun [plus](plus.html)(@NotNull()other: @NotNull()[Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>): @NotNull()[P](index.html) |
| [times](times.html) | [jvm]<br>@NotNull()<br>fun [times](times.html)(other: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): @NotNull()[P](index.html)<br>Multiplication by a number. |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Prints the coordinates. |


## Inheritors


| Name |
|---|
| [AbstractEuclideanPosition](../-abstract-euclidean-position/index.html) |


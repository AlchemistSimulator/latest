//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.positions](../index.md)/[AbstractPosition](index.md)

# AbstractPosition

[jvm]\
abstract class [AbstractPosition](index.md)<[P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)>?> : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)> 

N-dimensional position.

## Parameters

jvm

| | |
|---|---|
| <P> | actual type |

## Functions

| Name | Summary |
|---|---|
| [boundingBox](bounding-box.md) | [jvm]<br>fun [boundingBox](bounding-box.md)(range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[P](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)> |
| [distanceTo](distance-to.md) | [jvm]<br>fun [distanceTo](distance-to.md)(@NotNull()other: @NotNull()[P](index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [div](div.md) | [jvm]<br>@NotNull()<br>fun [div](div.md)(other: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): @NotNull()[P](index.md)<br>Division by a number. |
| [equals](equals.md) | [jvm]<br>fun [equals](equals.md)(o: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getCoordinate](get-coordinate.md) | [jvm]<br>fun [getCoordinate](get-coordinate.md)(dim: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getCoordinates](get-coordinates.md) | [jvm]<br>@NotNull()<br>fun [getCoordinates](get-coordinates.md)(): @NotNull()[Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [getDimensions](get-dimensions.md) | [jvm]<br>fun [getDimensions](get-dimensions.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [hashCode](hash-code.md) | [jvm]<br>fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [minus](minus.md) | [jvm]<br>@NotNull()<br>fun [minus](minus.md)(@NotNull()other: @NotNull()[P](index.md)): @NotNull()[P](index.md)<br>Same as [minus](minus.md), with the internal representation of other.<br>[jvm]<br>@NotNull()<br>fun [minus](minus.md)(@NotNull()other: @NotNull()[Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>): @NotNull()[P](index.md) |
| [plus](plus.md) | [jvm]<br>@NotNull()<br>fun [plus](plus.md)(@NotNull()other: @NotNull()[P](index.md)): @NotNull()[P](index.md)<br>Same as [plus](plus.md), with the internal representation of other.<br>[jvm]<br>@NotNull()<br>fun [plus](plus.md)(@NotNull()other: @NotNull()[Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>): @NotNull()[P](index.md) |
| [times](times.md) | [jvm]<br>@NotNull()<br>fun [times](times.md)(other: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): @NotNull()[P](index.md)<br>Multiplication by a number. |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Prints the coordinates. |

## Inheritors

| Name |
|---|
| [AbstractEuclideanPosition](../-abstract-euclidean-position/index.md) |

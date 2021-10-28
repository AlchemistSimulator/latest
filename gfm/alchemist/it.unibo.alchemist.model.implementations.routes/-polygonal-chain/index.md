//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.routes](../index.md)/[PolygonalChain](index.md)

# PolygonalChain

[jvm]\
open class [PolygonalChain](index.md)<[P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>?> : [Route](../../it.unibo.alchemist.model.interfaces/-route/index.md)<[P](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-constant-speed/index.md)> 

Abstract route implementation.

## Parameters

jvm

| | |
|---|---|
| <P> | the type of position that the route is composed |

## Constructors

| | |
|---|---|
| [PolygonalChain](-polygonal-chain.md) | [jvm]<br>@[SafeVarargs](https://docs.oracle.com/javase/8/docs/api/java/lang/SafeVarargs.html)()<br>open fun [PolygonalChain](-polygonal-chain.md)(positions: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[P](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-constant-speed/index.md)>)<br>the positions this route traverses |
| [PolygonalChain](-polygonal-chain.md) | [jvm]<br>open fun [PolygonalChain](-polygonal-chain.md)(positions: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[P](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-constant-speed/index.md)>)<br>the positions this route traverses |

## Functions

| Name | Summary |
|---|---|
| [equals](equals.md) | [jvm]<br>fun [equals](equals.md)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getPoint](get-point.md) | [jvm]<br>fun [getPoint](get-point.md)(step: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [P](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-constant-speed/index.md)<br>the step |
| [getPoints](get-points.md) | [jvm]<br>fun [getPoints](get-points.md)(): ImmutableList<[P](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-constant-speed/index.md)><br>the route as list of [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md) |
| [hashCode](hash-code.md) | [jvm]<br>fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [iterator](iterator.md) | [jvm]<br>fun [iterator](iterator.md)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[P](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-constant-speed/index.md)> |
| [length](length.md) | [jvm]<br>fun [length](length.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the length of the route |
| [size](size.md) | [jvm]<br>fun [size](size.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the number of points this route is made of |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)> |
| [stream](stream.md) | [jvm]<br>fun [stream](stream.md)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[P](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-constant-speed/index.md)><br>the route as stream of [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md) |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Prints the class name and the list of positions. |

## Inheritors

| Name |
|---|
| [GPSTraceImpl](../-g-p-s-trace-impl/index.md) |

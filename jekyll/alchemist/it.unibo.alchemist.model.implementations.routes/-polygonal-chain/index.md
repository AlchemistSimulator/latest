---
title: PolygonalChain
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.routes](../index.html)/[PolygonalChain](index.html)



# PolygonalChain



[jvm]\
open class [PolygonalChain](index.html)<[P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>?> : [Route](../../it.unibo.alchemist.model.interfaces/-route/index.html)<[P](../../it.unibo.alchemist/-supported-incarnations/get.html)> 

Abstract route implementation.



## Parameters


jvm

| | |
|---|---|
| <P> | the type of position that the route is composed |



## Constructors


| | |
|---|---|
| [PolygonalChain](-polygonal-chain.html) | [jvm]<br>@[SafeVarargs](https://docs.oracle.com/javase/8/docs/api/java/lang/SafeVarargs.html)()<br>open fun [PolygonalChain](-polygonal-chain.html)(positions: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[P](../../it.unibo.alchemist/-supported-incarnations/get.html)>)<br>the positions this route traverses |
| [PolygonalChain](-polygonal-chain.html) | [jvm]<br>open fun [PolygonalChain](-polygonal-chain.html)(positions: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[P](../../it.unibo.alchemist/-supported-incarnations/get.html)>)<br>the positions this route traverses |


## Functions


| Name | Summary |
|---|---|
| [equals](equals.html) | [jvm]<br>fun [equals](equals.html)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getPoint](get-point.html) | [jvm]<br>fun [getPoint](get-point.html)(step: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [P](../../it.unibo.alchemist/-supported-incarnations/get.html)<br>the step |
| [getPoints](get-points.html) | [jvm]<br>fun [getPoints](get-points.html)(): ImmutableList<[P](../../it.unibo.alchemist/-supported-incarnations/get.html)><br>the route as list of [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html) |
| [hashCode](hash-code.html) | [jvm]<br>fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [iterator](iterator.html) | [jvm]<br>fun [iterator](iterator.html)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[P](../../it.unibo.alchemist/-supported-incarnations/get.html)> |
| [length](length.html) | [jvm]<br>fun [length](length.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the length of the route |
| [size](size.html) | [jvm]<br>fun [size](size.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the number of points this route is made of |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)> |
| [stream](stream.html) | [jvm]<br>fun [stream](stream.html)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[P](../../it.unibo.alchemist/-supported-incarnations/get.html)><br>the route as stream of [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html) |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Prints the class name and the list of positions. |


## Inheritors


| Name |
|---|
| [GPSTraceImpl](../-g-p-s-trace-impl/index.html) |


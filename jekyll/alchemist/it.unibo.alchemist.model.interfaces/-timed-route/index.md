---
title: TimedRoute
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[TimedRoute](index.html)



# TimedRoute



[jvm]\
interface [TimedRoute](index.html)<[P](index.html) : [Position](../-position/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>?> : [Route](../-route/index.html)<[P](index.html)> 

Route with total trip time to cross it.



## Parameters


jvm

| | |
|---|---|
| <P> | type of position in the route |



## Functions


| Name | Summary |
|---|---|
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getPoint](../-route/get-point.html) | [jvm]<br>abstract fun [getPoint](../-route/get-point.html)(p: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [P](index.html) |
| [getPoints](../-route/get-points.html) | [jvm]<br>abstract fun [getPoints](../-route/get-points.html)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[P](index.html)> |
| [getTripTime](get-trip-time.html) | [jvm]<br>abstract fun [getTripTime](get-trip-time.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the total trip time |
| [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-straight-line-trace-dependant-speed/index.html)> |
| [length](../-route/length.html) | [jvm]<br>abstract fun [length](../-route/length.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [size](../-route/size.html) | [jvm]<br>abstract fun [size](../-route/size.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-straight-line-trace-dependant-speed/index.html)> |
| [stream](../-route/stream.html) | [jvm]<br>abstract fun [stream](../-route/stream.html)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[P](index.html)> |


## Inheritors


| Name |
|---|
| [GPSTrace](../-g-p-s-trace/index.html) |
| [GraphHopperRoute](../../it.unibo.alchemist.model.implementations.routes/-graph-hopper-route/index.html) |


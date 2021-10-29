---
title: FromGPSTrace
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.deployments](../index.html)/[FromGPSTrace](index.html)



# FromGPSTrace



[jvm]\
class [FromGPSTrace](index.html) : [Deployment](../-deployment/index.html)

Distributes nodes in the first positions of [it.unibo.alchemist.model.interfaces.GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.html).



## Constructors


| | |
|---|---|
| [FromGPSTrace](-from-g-p-s-trace.html) | [jvm]<br>open fun [FromGPSTrace](-from-g-p-s-trace.html)(nodeCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), path: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), cycle: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), normalizer: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), args: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>number of node request |


## Functions


| Name | Summary |
|---|---|
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.html) | [jvm]<br>open fun <[T](../-deployment/get-associated-linking-rule.html)> [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.html)(): [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html), [P](../../it.unibo.alchemist.model.interfaces/-timed-route/index.html)> |
| [iterator](../-deployment/iterator.html) | [jvm]<br>open fun [iterator](../-deployment/iterator.html)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[P](../../it.unibo.alchemist.model.interfaces/-timed-route/index.html)><br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)> |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)> |
| [stream](stream.html) | [jvm]<br>open fun [stream](stream.html)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)> |


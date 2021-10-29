---
title: Deployment
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.deployments](../index.html)/[Deployment](index.html)



# Deployment



[jvm]\
@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()



interface [Deployment](index.html)<[P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](../-circle/index.html)>?> : [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)<[P](../-circle/index.html)>



## Parameters


jvm

| | |
|---|---|
| <P> | position type |



## Functions


| Name | Summary |
|---|---|
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getAssociatedLinkingRule](get-associated-linking-rule.html) | [jvm]<br>@[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()<br>open fun <[T](get-associated-linking-rule.html)> [getAssociatedLinkingRule](get-associated-linking-rule.html)(): [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html), [P](../-circle/index.html)> |
| [iterator](iterator.html) | [jvm]<br>open fun [iterator](iterator.html)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[P](../-circle/index.html)> |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)> |
| [stream](stream.html) | [jvm]<br>abstract fun [stream](stream.html)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[P](../-circle/index.html)><br>a [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html) over the positions of this [Deployment](index.html) |


## Inheritors


| Name |
|---|
| [FromGPSTrace](../-from-g-p-s-trace/index.html) |
| [Point](../-point/index.html) |
| [AbstractCloseTo](../-abstract-close-to/index.html) |
| [AbstractRandomDeployment](../-abstract-random-deployment/index.html) |
| [CircularArc](../-circular-arc/index.html) |
| [GraphStreamDeployment](../-graph-stream-deployment/index.html) |
| [Grid](../-grid/index.html) |
| [SpecificPositions](../-specific-positions/index.html) |


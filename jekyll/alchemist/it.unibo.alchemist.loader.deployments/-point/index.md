---
title: Point
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.deployments](../index.html)/[Point](index.html)



# Point



[jvm]\
class [Point](index.html)<[P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](../../it.unibo.alchemist.loader.shapes/-circle/index.html)>?> : [Deployment](../-deployment/index.html)<[P](../../it.unibo.alchemist.loader.shapes/-circle/index.html)> 

A single node in a single point.



## Parameters


jvm

| | |
|---|---|
| <P> | position type |



## Constructors


| | |
|---|---|
| [Point](-point.html) | [jvm]<br>open fun [Point](-point.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.loader.shapes/-circle/index.html)>, x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>The [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html) |


## Functions


| Name | Summary |
|---|---|
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.html) | [jvm]<br>@[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()<br>open fun <[T](../-deployment/get-associated-linking-rule.html)> [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.html)(): [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html), [P](../../it.unibo.alchemist.loader.shapes/-circle/index.html)> |
| [iterator](../-deployment/iterator.html) | [jvm]<br>open fun [iterator](../-deployment/iterator.html)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[P](../../it.unibo.alchemist.loader.shapes/-circle/index.html)><br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)> |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)> |
| [stream](stream.html) | [jvm]<br>open fun [stream](stream.html)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[P](../../it.unibo.alchemist.loader.shapes/-circle/index.html)><br>a [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html) over the positions of this [Deployment](../-deployment/index.html) |


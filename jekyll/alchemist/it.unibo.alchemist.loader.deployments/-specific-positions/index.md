---
title: SpecificPositions
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.deployments](../index.html)/[SpecificPositions](index.html)



# SpecificPositions



[jvm]\
class [SpecificPositions](index.html)(**environment**: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<*, *>, **positions**: [Iterable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>) : [Deployment](../-deployment/index.html)<[Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<*>> 

Given an environment and a list of list of numbers, it creates a list of the right position type for the environment.



## Constructors


| | |
|---|---|
| [SpecificPositions](-specific-positions.html) | [jvm]<br>fun [SpecificPositions](-specific-positions.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<*, *>, vararg positions: [Iterable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>) |


## Functions


| Name | Summary |
|---|---|
| [forEach](index.html#1001862243%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](index.html#1001862243%2FFunctions%2F-134779887)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<*>>) |
| [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.html) | [jvm]<br>@[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()<br>open fun <[T](../-deployment/get-associated-linking-rule.html) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.html)(): [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.html)<[T](../-deployment/get-associated-linking-rule.html), [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<*>>? |
| [iterator](../-deployment/iterator.html) | [jvm]<br>open operator override fun [iterator](../-deployment/iterator.html)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<*>> |
| [spliterator](../-close-to-g-p-s-trace/index.html#-1387152138%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../-close-to-g-p-s-trace/index.html#-1387152138%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<*>> |
| [stream](stream.html) | [jvm]<br>open override fun [stream](stream.html)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<*>><br>a [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html) over the positions of this [Deployment](../-deployment/index.html) |


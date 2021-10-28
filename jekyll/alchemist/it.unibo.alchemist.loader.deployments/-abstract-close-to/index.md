---
title: AbstractCloseTo
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.deployments](../index.html)/[AbstractCloseTo](index.html)



# AbstractCloseTo



[jvm]\
abstract class [AbstractCloseTo](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>>(**randomGenerator**: RandomGenerator, **environment**: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](index.html)>, **nodeCount**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **variance**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [Deployment](../-deployment/index.html)<[P](index.html)> 

A generic [Deployment](../-deployment/index.html) that displaces a certain nodeCount of nodes in the proximity of a number of sources. Higher variance implies higher dispersion. Subclasses must identify the sources



## Constructors


| | |
|---|---|
| [AbstractCloseTo](-abstract-close-to.html) | [jvm]<br>fun <[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>> [AbstractCloseTo](-abstract-close-to.html)(randomGenerator: RandomGenerator, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](index.html)>, nodeCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), variance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |


## Functions


| Name | Summary |
|---|---|
| [forEach](../-graph-stream-deployment/index.html#-1888597325%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](../-graph-stream-deployment/index.html#-1888597325%2FFunctions%2F-134779887)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [P](index.html)>) |
| [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.html) | [jvm]<br>@[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()<br>open fun <[T](../-deployment/get-associated-linking-rule.html) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.html)(): [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.html)<[T](../-deployment/get-associated-linking-rule.html), [P](index.html)>? |
| [iterator](../-deployment/iterator.html) | [jvm]<br>open operator override fun [iterator](../-deployment/iterator.html)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[P](index.html)> |
| [spliterator](../-close-to-g-p-s-trace/index.html#-1387152138%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../-close-to-g-p-s-trace/index.html#-1387152138%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[P](index.html)> |
| [stream](stream.html) | [jvm]<br>override fun [stream](stream.html)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[P](index.html)><br>a [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html) over the positions of this [Deployment](../-deployment/index.html) |


## Inheritors


| Name |
|---|
| [CloseToGPSTrace](../-close-to-g-p-s-trace/index.html) |
| [CloseToAlreadyDeployed](../-close-to-already-deployed/index.html) |


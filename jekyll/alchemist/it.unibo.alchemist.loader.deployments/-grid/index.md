---
title: Grid
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.deployments](../index.html)/[Grid](index.html)



# Grid



[jvm]\
open class [Grid](index.html)@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()constructor(**environment**: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<*, *>, **randomGenerator**: RandomGenerator, **xStart**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **yStart**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **xEnd**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **yEnd**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **xStep**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **yStep**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **xRand**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **yRand**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **xShift**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **yShift**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [Deployment](../-deployment/index.html)<[Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<*>> 

A (possibly randomized) grid of nodes.



## Parameters


jvm

| | |
|---|---|
| environment | the {@link Environment} |
| randomGenerator | the {@link RandomGenerator} |
| xStart | the start x position |
| yStart | the start y position |
| xEnd | the end x position |
| yEnd | the end y position |
| xStep | how distant on the x axis (on average) nodes should be |
| yStep | how distant on the y axis (on average) nodes should be |
| xRand | how randomized should be positions along the x axis |
| yRand | how randomized should be positions along the y axis |
| xShift | how shifted should be positions between lines |
| yShift | how shifted should be positions along columns |



## Constructors


| | |
|---|---|
| [Grid](-grid.html) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun [Grid](-grid.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<*, *>, randomGenerator: RandomGenerator, xStart: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), yStart: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), xEnd: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), yEnd: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), xStep: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), yStep: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), xRand: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, yRand: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, xShift: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, yShift: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0)<br>    the {@link Environment} |


## Functions


| Name | Summary |
|---|---|
| [forEach](../-specific-positions/index.html#1001862243%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](../-specific-positions/index.html#1001862243%2FFunctions%2F-134779887)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<*>>) |
| [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.html) | [jvm]<br>@[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()<br>open fun <[T](../-deployment/get-associated-linking-rule.html) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.html)(): [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.html)<[T](../-deployment/get-associated-linking-rule.html), [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<*>>? |
| [iterator](../-deployment/iterator.html) | [jvm]<br>open operator override fun [iterator](../-deployment/iterator.html)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<*>> |
| [spliterator](../-close-to-g-p-s-trace/index.html#-1387152138%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../-close-to-g-p-s-trace/index.html#-1387152138%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<*>> |
| [stream](stream.html) | [jvm]<br>open override fun [stream](stream.html)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<*>><br>a [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html) over the positions of this [Deployment](../-deployment/index.html) |


//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.deployments](../index.md)/[Grid](index.md)

# Grid

[jvm]\
open class [Grid](index.md)@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()constructor(**environment**: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<*, *>, **randomGenerator**: RandomGenerator, **xStart**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **yStart**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **xEnd**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **yEnd**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **xStep**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **yStep**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **xRand**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **yRand**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **xShift**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **yShift**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [Deployment](../-deployment/index.md)<[Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<*>> 

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
| [Grid](-grid.md) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun [Grid](-grid.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<*, *>, randomGenerator: RandomGenerator, xStart: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), yStart: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), xEnd: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), yEnd: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), xStep: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), yStep: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), xRand: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, yRand: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, xShift: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, yShift: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0)<br>    the {@link Environment} |

## Functions

| Name | Summary |
|---|---|
| [forEach](../-specific-positions/index.md#1001862243%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../-specific-positions/index.md#1001862243%2FFunctions%2F-267951372)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<*>>) |
| [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.md) | [jvm]<br>@[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()<br>open fun <[T](../-deployment/get-associated-linking-rule.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.md)(): [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.md)<[T](../-deployment/get-associated-linking-rule.md), [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<*>>? |
| [iterator](../-deployment/iterator.md) | [jvm]<br>open operator override fun [iterator](../-deployment/iterator.md)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<*>> |
| [spliterator](../-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<*>> |
| [stream](stream.md) | [jvm]<br>open override fun [stream](stream.md)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<*>><br>a [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html) over the positions of this [Deployment](../-deployment/index.md) |

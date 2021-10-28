//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.deployments](../index.md)/[SpecificPositions](index.md)

# SpecificPositions

[jvm]\
class [SpecificPositions](index.md)(**environment**: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<*, *>, **positions**: [Iterable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>) : [Deployment](../-deployment/index.md)<[Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<*>> 

Given an environment and a list of list of numbers, it creates a list of the right position type for the environment.

## Constructors

| | |
|---|---|
| [SpecificPositions](-specific-positions.md) | [jvm]<br>fun [SpecificPositions](-specific-positions.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<*, *>, vararg positions: [Iterable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>) |

## Functions

| Name | Summary |
|---|---|
| [forEach](index.md#1001862243%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](index.md#1001862243%2FFunctions%2F-267951372)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<*>>) |
| [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.md) | [jvm]<br>@[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()<br>open fun <[T](../-deployment/get-associated-linking-rule.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.md)(): [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.md)<[T](../-deployment/get-associated-linking-rule.md), [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<*>>? |
| [iterator](../-deployment/iterator.md) | [jvm]<br>open operator override fun [iterator](../-deployment/iterator.md)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<*>> |
| [spliterator](../-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<*>> |
| [stream](stream.md) | [jvm]<br>open override fun [stream](stream.md)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<*>><br>a [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html) over the positions of this [Deployment](../-deployment/index.md) |

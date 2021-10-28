//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.deployments](../index.md)/[CloseToAlreadyDeployed](index.md)

# CloseToAlreadyDeployed

[jvm]\
class [CloseToAlreadyDeployed](index.md)<[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>>(**randomGenerator**: RandomGenerator, **environment**: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [P](index.md)>, **nodeCount**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **variance**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [AbstractCloseTo](../-abstract-close-to/index.md)<[T](index.md), [P](index.md)> 

This [Deployment](../-deployment/index.md) places new nodes in the proximity of those already included in the environment. Behaviour if there are no nodes already inserted is undefined.

## Constructors

| | |
|---|---|
| [CloseToAlreadyDeployed](-close-to-already-deployed.md) | [jvm]<br>fun <[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>> [CloseToAlreadyDeployed](-close-to-already-deployed.md)(randomGenerator: RandomGenerator, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [P](index.md)>, nodeCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), variance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |

## Functions

| Name | Summary |
|---|---|
| [forEach](../-graph-stream-deployment/index.md#-1888597325%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../-graph-stream-deployment/index.md#-1888597325%2FFunctions%2F-267951372)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [P](index.md)>) |
| [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.md) | [jvm]<br>@[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()<br>open fun <[T](../-deployment/get-associated-linking-rule.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.md)(): [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.md)<[T](../-deployment/get-associated-linking-rule.md), [P](index.md)>? |
| [iterator](../-deployment/iterator.md) | [jvm]<br>open operator override fun [iterator](../-deployment/iterator.md)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[P](index.md)> |
| [spliterator](../-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[P](index.md)> |
| [stream](../-abstract-close-to/stream.md) | [jvm]<br>override fun [stream](../-abstract-close-to/stream.md)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[P](index.md)><br>a [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html) over the positions of this [Deployment](../-deployment/index.md) |

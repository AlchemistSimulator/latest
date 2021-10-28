//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.deployments](../index.md)/[AbstractRandomDeployment](index.md)

# AbstractRandomDeployment

[jvm]\
abstract class [AbstractRandomDeployment](index.md)<[P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<out [P](index.md)>>(**environment**: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<*, [P](index.md)>, **randomGenerator**: RandomGenerator, **nodeCount**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [Deployment](../-deployment/index.md)<[P](index.md)>

## Parameters

jvm

| | |
|---|---|
| environment | the [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md) |
| randomGenerator | the RandomGenerator |
| nodeCount | the number of nodes |
|  | <P> |

## Constructors

| | |
|---|---|
| [AbstractRandomDeployment](-abstract-random-deployment.md) | [jvm]<br>fun <[P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<out [P](index.md)>> [AbstractRandomDeployment](-abstract-random-deployment.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<*, [P](index.md)>, randomGenerator: RandomGenerator, nodeCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>the [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md) |

## Functions

| Name | Summary |
|---|---|
| [forEach](../-graph-stream-deployment/index.md#-1888597325%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../-graph-stream-deployment/index.md#-1888597325%2FFunctions%2F-267951372)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [P](index.md)>) |
| [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.md) | [jvm]<br>@[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()<br>open fun <[T](../-deployment/get-associated-linking-rule.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.md)(): [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.md)<[T](../-deployment/get-associated-linking-rule.md), [P](index.md)>? |
| [iterator](../-deployment/iterator.md) | [jvm]<br>open operator override fun [iterator](../-deployment/iterator.md)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[P](index.md)> |
| [spliterator](../-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[P](index.md)> |
| [stream](stream.md) | [jvm]<br>open override fun [stream](stream.md)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[P](index.md)><br>a [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html) over the positions of this [Deployment](../-deployment/index.md) |

## Inheritors

| Name |
|---|
| [Circle](../-circle/index.md) |
| [Rectangle](../-rectangle/index.md) |
| [Polygon](../-polygon/index.md) |

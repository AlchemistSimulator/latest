//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.deployments](../index.md)/[Polygon](index.md)

# Polygon

[jvm]\
open class [Polygon](index.md)<[P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](index.md)>>(**environment**: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<*, [P](index.md)>, **randomGenerator**: RandomGenerator, **nodes**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **pointsInput**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<*>) : [AbstractRandomDeployment](../-abstract-random-deployment/index.md)<[P](index.md)> 

Creates a new Polygon with the given points.

## Parameters

jvm

| | |
|---|---|
| nodes | the count of nodes that need to get displaced inside the polygon |
| pointsInput | the points of the polygon. The class does not check for "malformed" polygons (e.g. with intersections). If the provided points do not represent a valid polygon in bidimensional space, the behaviour of this class is undefined. There polygon is closed automatically (there is no need to pass the first point also as last element). |

## Constructors

| | |
|---|---|
| [Polygon](-polygon.md) | [jvm]<br>fun <[P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](index.md)>> [Polygon](-polygon.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<*, [P](index.md)>, randomGenerator: RandomGenerator, nodes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), pointsInput: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<*>)<br>the count of nodes that need to get displaced inside the polygon |

## Functions

| Name | Summary |
|---|---|
| [forEach](index.md#570985313%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](index.md#570985313%2FFunctions%2F-267951372)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [P](index.md)>) |
| [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.md) | [jvm]<br>@[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()<br>open fun <[T](../-deployment/get-associated-linking-rule.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.md)(): [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.md)<[T](../-deployment/get-associated-linking-rule.md), [P](index.md)>? |
| [iterator](../-deployment/iterator.md) | [jvm]<br>open operator override fun [iterator](../-deployment/iterator.md)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[P](index.md)> |
| [spliterator](../-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[P](index.md)> |
| [stream](../-abstract-random-deployment/stream.md) | [jvm]<br>open override fun [stream](../-abstract-random-deployment/stream.md)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[P](index.md)><br>a [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html) over the positions of this [Deployment](../-deployment/index.md) |

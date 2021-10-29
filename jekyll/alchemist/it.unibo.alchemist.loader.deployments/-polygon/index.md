---
title: Polygon
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.deployments](../index.html)/[Polygon](index.html)



# Polygon



[jvm]\
open class [Polygon](index.html)<[P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](index.html)>>(**environment**: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<*, [P](index.html)>, **randomGenerator**: RandomGenerator, **nodes**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **pointsInput**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<*>) : [AbstractRandomDeployment](../-abstract-random-deployment/index.html)<[P](index.html)> 

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
| [Polygon](-polygon.html) | [jvm]<br>fun <[P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](index.html)>> [Polygon](-polygon.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<*, [P](index.html)>, randomGenerator: RandomGenerator, nodes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), pointsInput: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<*>)<br>the count of nodes that need to get displaced inside the polygon |


## Functions


| Name | Summary |
|---|---|
| [forEach](index.html#570985313%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](index.html#570985313%2FFunctions%2F-134779887)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [P](index.html)>) |
| [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.html) | [jvm]<br>@[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()<br>open fun <[T](../-deployment/get-associated-linking-rule.html) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.html)(): [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.html)<[T](../-deployment/get-associated-linking-rule.html), [P](index.html)>? |
| [iterator](../-deployment/iterator.html) | [jvm]<br>open operator override fun [iterator](../-deployment/iterator.html)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[P](index.html)> |
| [spliterator](../-close-to-g-p-s-trace/index.html#-1387152138%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../-close-to-g-p-s-trace/index.html#-1387152138%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[P](index.html)> |
| [stream](../-abstract-random-deployment/stream.html) | [jvm]<br>open override fun [stream](../-abstract-random-deployment/stream.html)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[P](index.html)><br>a [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html) over the positions of this [Deployment](../-deployment/index.html) |


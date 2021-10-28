---
title: CircularArc
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.deployments](../index.html)/[CircularArc](index.html)



# CircularArc



[jvm]\
data class [CircularArc](index.html)<[P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](index.html)>>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()constructor(**environment**: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<*, [P](index.html)>, **randomGenerator**: RandomGenerator, **nodeCount**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **centerX**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **centerY**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **radius**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **radiusRandomness**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **angleRandomness**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **startAngle**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **endAngle**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [Deployment](../-deployment/index.html)<[P](index.html)> 

Displaces the nodes in the [environment](environment.html) in a circular arc, given a [nodeCount](node-count.html), the coordinates of the circle's center [centerX](center-x.html) and [centerY](center-y.html), the circle's radius [radius](radius.html), perturbation randomness (uniform, generated via [randomGenerator](random-generator.html)) for radius [radiusRandomness](radius-randomness.html) and for angle [angleRandomness](angle-randomness.html), a [startAngle](start-angle.html), and an [endAngle](end-angle.html).



Default values generate a uniform deployment on a circumference.



## Constructors


| | |
|---|---|
| [CircularArc](-circular-arc.html) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun <[P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](index.html)>> [CircularArc](-circular-arc.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<*, [P](index.html)>, randomGenerator: RandomGenerator, nodeCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), centerX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, centerY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0, radiusRandomness: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, angleRandomness: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, startAngle: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, endAngle: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 2 * PI) |


## Functions


| Name | Summary |
|---|---|
| [forEach](../-polygon/index.html#570985313%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](../-polygon/index.html#570985313%2FFunctions%2F-134779887)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [P](index.html)>) |
| [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.html) | [jvm]<br>@[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()<br>open fun <[T](../-deployment/get-associated-linking-rule.html) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.html)(): [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.html)<[T](../-deployment/get-associated-linking-rule.html), [P](index.html)>? |
| [iterator](../-deployment/iterator.html) | [jvm]<br>open operator override fun [iterator](../-deployment/iterator.html)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[P](index.html)> |
| [spliterator](../-close-to-g-p-s-trace/index.html#-1387152138%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../-close-to-g-p-s-trace/index.html#-1387152138%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[P](index.html)> |
| [stream](stream.html) | [jvm]<br>open override fun [stream](stream.html)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[P](index.html)> |


## Properties


| Name | Summary |
|---|---|
| [angleRandomness](angle-randomness.html) | [jvm]<br>val [angleRandomness](angle-randomness.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0 |
| [centerX](center-x.html) | [jvm]<br>val [centerX](center-x.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0 |
| [centerY](center-y.html) | [jvm]<br>val [centerY](center-y.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0 |
| [endAngle](end-angle.html) | [jvm]<br>val [endAngle](end-angle.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [environment](environment.html) | [jvm]<br>val [environment](environment.html): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<*, [P](index.html)> |
| [nodeCount](node-count.html) | [jvm]<br>val [nodeCount](node-count.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [radius](radius.html) | [jvm]<br>val [radius](radius.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0 |
| [radiusRandomness](radius-randomness.html) | [jvm]<br>val [radiusRandomness](radius-randomness.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0 |
| [randomGenerator](random-generator.html) | [jvm]<br>val [randomGenerator](random-generator.html): RandomGenerator |
| [startAngle](start-angle.html) | [jvm]<br>val [startAngle](start-angle.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0 |


//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.deployments](../index.md)/[CircularArc](index.md)

# CircularArc

[jvm]\
data class [CircularArc](index.md)<[P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](index.md)>>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()constructor(**environment**: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<*, [P](index.md)>, **randomGenerator**: RandomGenerator, **nodeCount**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **centerX**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **centerY**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **radius**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **radiusRandomness**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **angleRandomness**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **startAngle**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **endAngle**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [Deployment](../-deployment/index.md)<[P](index.md)> 

Displaces the nodes in the [environment](environment.md) in a circular arc, given a [nodeCount](node-count.md), the coordinates of the circle's center [centerX](center-x.md) and [centerY](center-y.md), the circle's radius [radius](radius.md), perturbation randomness (uniform, generated via [randomGenerator](random-generator.md)) for radius [radiusRandomness](radius-randomness.md) and for angle [angleRandomness](angle-randomness.md), a [startAngle](start-angle.md), and an [endAngle](end-angle.md).

Default values generate a uniform deployment on a circumference.

## Constructors

| | |
|---|---|
| [CircularArc](-circular-arc.md) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun <[P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](index.md)>> [CircularArc](-circular-arc.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<*, [P](index.md)>, randomGenerator: RandomGenerator, nodeCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), centerX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, centerY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0, radiusRandomness: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, angleRandomness: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, startAngle: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, endAngle: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 2 * PI) |

## Functions

| Name | Summary |
|---|---|
| [forEach](../-polygon/index.md#570985313%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../-polygon/index.md#570985313%2FFunctions%2F-267951372)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [P](index.md)>) |
| [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.md) | [jvm]<br>@[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()<br>open fun <[T](../-deployment/get-associated-linking-rule.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.md)(): [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.md)<[T](../-deployment/get-associated-linking-rule.md), [P](index.md)>? |
| [iterator](../-deployment/iterator.md) | [jvm]<br>open operator override fun [iterator](../-deployment/iterator.md)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[P](index.md)> |
| [spliterator](../-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[P](index.md)> |
| [stream](stream.md) | [jvm]<br>open override fun [stream](stream.md)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[P](index.md)> |

## Properties

| Name | Summary |
|---|---|
| [angleRandomness](angle-randomness.md) | [jvm]<br>val [angleRandomness](angle-randomness.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0 |
| [centerX](center-x.md) | [jvm]<br>val [centerX](center-x.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0 |
| [centerY](center-y.md) | [jvm]<br>val [centerY](center-y.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0 |
| [endAngle](end-angle.md) | [jvm]<br>val [endAngle](end-angle.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [environment](environment.md) | [jvm]<br>val [environment](environment.md): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<*, [P](index.md)> |
| [nodeCount](node-count.md) | [jvm]<br>val [nodeCount](node-count.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [radius](radius.md) | [jvm]<br>val [radius](radius.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0 |
| [radiusRandomness](radius-randomness.md) | [jvm]<br>val [radiusRandomness](radius-randomness.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0 |
| [randomGenerator](random-generator.md) | [jvm]<br>val [randomGenerator](random-generator.md): RandomGenerator |
| [startAngle](start-angle.md) | [jvm]<br>val [startAngle](start-angle.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0 |

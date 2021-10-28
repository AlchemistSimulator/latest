//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.deployments](../index.md)/[CloseToGPSTrace](index.md)

# CloseToGPSTrace

[jvm]\
class [CloseToGPSTrace](index.md)<[T](index.md)>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()constructor(**randomGenerator**: RandomGenerator, **environment**: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)>, **nodeCount**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **variance**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **from**: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), **interval**: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), **to**: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), **gpsFilePath**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **normalizerClass**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **normalizerArguments**: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)) : [AbstractCloseTo](../-abstract-close-to/index.md)<[T](index.md), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)> 

This [Deployment](../-deployment/index.md) displaces nodes in the proximity of a GPS trace. Given a time interval from some time [to](to.md) another, it creates a [TraceLoader](../../it.unibo.alchemist.boundary.gpsload.impl/-trace-loader/index.md), then uses the points in the interval to generate the sources for a Gaussian bivariate function and uses its probability density to deploy. Higher variance spreads nodes farther away from the trace with higher probability.

## Constructors

| | |
|---|---|
| [CloseToGPSTrace](-close-to-g-p-s-trace.md) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun <[T](index.md)> [CloseToGPSTrace](-close-to-g-p-s-trace.md)(randomGenerator: RandomGenerator, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)>, nodeCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), variance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), from: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md) = Time.ZERO, interval: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md) = DoubleTime(1.0), to: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md) = Time.INFINITY, gpsFilePath: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), normalizerClass: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), vararg normalizerArguments: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)) |

## Functions

| Name | Summary |
|---|---|
| [forEach](index.md#-1422480456%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](index.md#-1422480456%2FFunctions%2F-267951372)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)>) |
| [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.md) | [jvm]<br>@[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()<br>open fun <[T](../-deployment/get-associated-linking-rule.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.md)(): [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.md)<[T](../-deployment/get-associated-linking-rule.md), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)>? |
| [iterator](../-deployment/iterator.md) | [jvm]<br>open operator override fun [iterator](../-deployment/iterator.md)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)> |
| [spliterator](index.md#-1387152138%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](index.md#-1387152138%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)> |
| [stream](../-abstract-close-to/stream.md) | [jvm]<br>override fun [stream](../-abstract-close-to/stream.md)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)> |

## Properties

| Name | Summary |
|---|---|
| [to](to.md) | [jvm]<br>val [to](to.md): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md) |

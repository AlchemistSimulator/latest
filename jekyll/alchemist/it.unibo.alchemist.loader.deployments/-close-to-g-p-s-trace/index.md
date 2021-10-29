---
title: CloseToGPSTrace
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.deployments](../index.html)/[CloseToGPSTrace](index.html)



# CloseToGPSTrace



[jvm]\
class [CloseToGPSTrace](index.html)<[T](index.html)>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()constructor(**randomGenerator**: RandomGenerator, **environment**: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>, **nodeCount**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **variance**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **from**: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), **interval**: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), **to**: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), **gpsFilePath**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **normalizerClass**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **normalizerArguments**: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)) : [AbstractCloseTo](../-abstract-close-to/index.html)<[T](index.html), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)> 

This [Deployment](../-deployment/index.html) displaces nodes in the proximity of a GPS trace. Given a time interval from some time [to](to.html) another, it creates a [TraceLoader](../../it.unibo.alchemist.boundary.gpsload.impl/-trace-loader/index.html), then uses the points in the interval to generate the sources for a Gaussian bivariate function and uses its probability density to deploy. Higher variance spreads nodes farther away from the trace with higher probability.



## Constructors


| | |
|---|---|
| [CloseToGPSTrace](-close-to-g-p-s-trace.html) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun <[T](index.html)> [CloseToGPSTrace](-close-to-g-p-s-trace.html)(randomGenerator: RandomGenerator, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>, nodeCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), variance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), from: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html) = Time.ZERO, interval: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html) = DoubleTime(1.0), to: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html) = Time.INFINITY, gpsFilePath: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), normalizerClass: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), vararg normalizerArguments: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)) |


## Functions


| Name | Summary |
|---|---|
| [forEach](index.html#-1422480456%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](index.html#-1422480456%2FFunctions%2F-134779887)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>) |
| [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.html) | [jvm]<br>@[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()<br>open fun <[T](../-deployment/get-associated-linking-rule.html) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.html)(): [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.html)<[T](../-deployment/get-associated-linking-rule.html), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>? |
| [iterator](../-deployment/iterator.html) | [jvm]<br>open operator override fun [iterator](../-deployment/iterator.html)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)> |
| [spliterator](index.html#-1387152138%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](index.html#-1387152138%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)> |
| [stream](../-abstract-close-to/stream.html) | [jvm]<br>override fun [stream](../-abstract-close-to/stream.html)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)> |


## Properties


| Name | Summary |
|---|---|
| [to](to.html) | [jvm]<br>val [to](to.html): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html) |


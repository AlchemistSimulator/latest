//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.linkingrules](../index.md)/[AdaptiveRange](index.md)

# AdaptiveRange

[jvm]\
open class [AdaptiveRange](index.md)<[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](../../it.unibo.alchemist.model.interfaces/-route/index.md)>?> : [ConnectWithinDistance](../-connect-within-distance/index.md)<[T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md), [P](../../it.unibo.alchemist.model.interfaces/-route/index.md)> 

This linking rule dynamically searches for the best radius for each device, in such a way that it connects to a certain number of devices.

## Parameters

jvm

| | |
|---|---|
| <T> | Concentration type |
| <P> | [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md) type |

## Constructors

| | |
|---|---|
| [AdaptiveRange](-adaptive-range.md) | [jvm]<br>open fun [AdaptiveRange](-adaptive-range.md)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), minrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maxrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), num: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>default radius in metres |
| [AdaptiveRange](-adaptive-range.md) | [jvm]<br>open fun [AdaptiveRange](-adaptive-range.md)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), minrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maxrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), num: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), adjustment: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>default radius in metres |
| [AdaptiveRange](-adaptive-range.md) | [jvm]<br>open fun [AdaptiveRange](-adaptive-range.md)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), minrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), num: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>default radius in metres |
| [AdaptiveRange](-adaptive-range.md) | [jvm]<br>open fun [AdaptiveRange](-adaptive-range.md)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), minrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), num: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), adjustment: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>default radius in metres |
| [AdaptiveRange](-adaptive-range.md) | [jvm]<br>open fun [AdaptiveRange](-adaptive-range.md)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), num: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>default radius in metres |
| [AdaptiveRange](-adaptive-range.md) | [jvm]<br>open fun [AdaptiveRange](-adaptive-range.md)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), num: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), adjustment: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>default radius in metres |

## Functions

| Name | Summary |
|---|---|
| [computeNeighborhood](compute-neighborhood.md) | [jvm]<br>fun [computeNeighborhood](compute-neighborhood.md)(center: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md), [P](../../it.unibo.alchemist.model.interfaces/-route/index.md)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.md)<[T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md)><br>Subclasses may change the way a neighborhood is computed.<br>[jvm]<br>abstract fun [computeNeighborhood](../../it.unibo.alchemist.model.interfaces/-linking-rule/compute-neighborhood.md)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md)>, p1: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md), [P](../../it.unibo.alchemist.model.interfaces/-route/index.md)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.md)<[T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md)> |
| [isLocallyConsistent](../-abstract-locally-consistent-linking-rule/is-locally-consistent.md) | [jvm]<br>fun [isLocallyConsistent](../-abstract-locally-consistent-linking-rule/is-locally-consistent.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>abstract fun [isLocallyConsistent](../../it.unibo.alchemist.model.interfaces/-linking-rule/is-locally-consistent.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

## Properties

| Name | Summary |
|---|---|
| [DEFAULT_ADJUSTMENT](-d-e-f-a-u-l-t_-a-d-j-u-s-t-m-e-n-t.md) | [jvm]<br>val [DEFAULT_ADJUSTMENT](-d-e-f-a-u-l-t_-a-d-j-u-s-t-m-e-n-t.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Default adjustment. |
| [DEFAULT_MAXRANGE](-d-e-f-a-u-l-t_-m-a-x-r-a-n-g-e.md) | [jvm]<br>val [DEFAULT_MAXRANGE](-d-e-f-a-u-l-t_-m-a-x-r-a-n-g-e.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Default maximum range. |
| [DEFAULT_MINRANGE](-d-e-f-a-u-l-t_-m-i-n-r-a-n-g-e.md) | [jvm]<br>val [DEFAULT_MINRANGE](-d-e-f-a-u-l-t_-m-i-n-r-a-n-g-e.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Default minimum range. |

## Inheritors

| Name |
|---|
| [SelectiveAdaptiveRange](../-selective-adaptive-range/index.md) |

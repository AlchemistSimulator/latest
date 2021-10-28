---
title: AdaptiveRange
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.linkingrules](../index.html)/[AdaptiveRange](index.html)



# AdaptiveRange



[jvm]\
open class [AdaptiveRange](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>?> : [ConnectWithinDistance](../-connect-within-distance/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html), [P](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)> 

This linking rule dynamically searches for the best radius for each device, in such a way that it connects to a certain number of devices.



## Parameters


jvm

| | |
|---|---|
| <T> | Concentration type |
| <P> | [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html) type |



## Constructors


| | |
|---|---|
| [AdaptiveRange](-adaptive-range.html) | [jvm]<br>open fun [AdaptiveRange](-adaptive-range.html)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), minrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maxrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), num: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>default radius in metres |
| [AdaptiveRange](-adaptive-range.html) | [jvm]<br>open fun [AdaptiveRange](-adaptive-range.html)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), minrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maxrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), num: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), adjustment: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>default radius in metres |
| [AdaptiveRange](-adaptive-range.html) | [jvm]<br>open fun [AdaptiveRange](-adaptive-range.html)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), minrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), num: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>default radius in metres |
| [AdaptiveRange](-adaptive-range.html) | [jvm]<br>open fun [AdaptiveRange](-adaptive-range.html)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), minrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), num: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), adjustment: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>default radius in metres |
| [AdaptiveRange](-adaptive-range.html) | [jvm]<br>open fun [AdaptiveRange](-adaptive-range.html)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), num: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>default radius in metres |
| [AdaptiveRange](-adaptive-range.html) | [jvm]<br>open fun [AdaptiveRange](-adaptive-range.html)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), num: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), adjustment: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>default radius in metres |


## Functions


| Name | Summary |
|---|---|
| [computeNeighborhood](compute-neighborhood.html) | [jvm]<br>fun [computeNeighborhood](compute-neighborhood.html)(center: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html), [P](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)><br>Subclasses may change the way a neighborhood is computed.<br>[jvm]<br>abstract fun [computeNeighborhood](../../it.unibo.alchemist.model.interfaces/-linking-rule/compute-neighborhood.html)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>, p1: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html), [P](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)> |
| [isLocallyConsistent](../-abstract-locally-consistent-linking-rule/is-locally-consistent.html) | [jvm]<br>fun [isLocallyConsistent](../-abstract-locally-consistent-linking-rule/is-locally-consistent.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>abstract fun [isLocallyConsistent](../../it.unibo.alchemist.model.interfaces/-linking-rule/is-locally-consistent.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |


## Properties


| Name | Summary |
|---|---|
| [DEFAULT_ADJUSTMENT](-d-e-f-a-u-l-t_-a-d-j-u-s-t-m-e-n-t.html) | [jvm]<br>val [DEFAULT_ADJUSTMENT](-d-e-f-a-u-l-t_-a-d-j-u-s-t-m-e-n-t.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Default adjustment. |
| [DEFAULT_MAXRANGE](-d-e-f-a-u-l-t_-m-a-x-r-a-n-g-e.html) | [jvm]<br>val [DEFAULT_MAXRANGE](-d-e-f-a-u-l-t_-m-a-x-r-a-n-g-e.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Default maximum range. |
| [DEFAULT_MINRANGE](-d-e-f-a-u-l-t_-m-i-n-r-a-n-g-e.html) | [jvm]<br>val [DEFAULT_MINRANGE](-d-e-f-a-u-l-t_-m-i-n-r-a-n-g-e.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Default minimum range. |


## Inheritors


| Name |
|---|
| [SelectiveAdaptiveRange](../-selective-adaptive-range/index.html) |


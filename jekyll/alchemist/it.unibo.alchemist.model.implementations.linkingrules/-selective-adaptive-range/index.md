---
title: SelectiveAdaptiveRange
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.linkingrules](../index.html)/[SelectiveAdaptiveRange](index.html)



# SelectiveAdaptiveRange



[jvm]\
open class [SelectiveAdaptiveRange](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../../it.unibo.alchemist.model/-s-a-p-e-r-e-incarnation/index.html)>?> : [AdaptiveRange](../-adaptive-range/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html), [P](../../it.unibo.alchemist.model/-s-a-p-e-r-e-incarnation/index.html)>



## Parameters


jvm

| | |
|---|---|
| <P> | position type |
| <T> | concentration type |



## Constructors


| | |
|---|---|
| [SelectiveAdaptiveRange](-selective-adaptive-range.html) | [jvm]<br>open fun [SelectiveAdaptiveRange](-selective-adaptive-range.html)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), minrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maxrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), desiredNeighborsCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>default radius in metres |
| [SelectiveAdaptiveRange](-selective-adaptive-range.html) | [jvm]<br>open fun [SelectiveAdaptiveRange](-selective-adaptive-range.html)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), minrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maxrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), desiredNeighborsCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), adjustment: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>default radius in metres |
| [SelectiveAdaptiveRange](-selective-adaptive-range.html) | [jvm]<br>open fun [SelectiveAdaptiveRange](-selective-adaptive-range.html)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), minrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maxrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), desiredNeighborsCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), adjustment: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), molType: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>default radius in metres |
| [SelectiveAdaptiveRange](-selective-adaptive-range.html) | [jvm]<br>open fun [SelectiveAdaptiveRange](-selective-adaptive-range.html)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), minrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), desiredNeighborsCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>default radius in metres |
| [SelectiveAdaptiveRange](-selective-adaptive-range.html) | [jvm]<br>open fun [SelectiveAdaptiveRange](-selective-adaptive-range.html)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), minrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), desiredNeighborsCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), adjustment: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>default radius in metres |
| [SelectiveAdaptiveRange](-selective-adaptive-range.html) | [jvm]<br>open fun [SelectiveAdaptiveRange](-selective-adaptive-range.html)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), desiredNeighborsCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>default radius in metres |
| [SelectiveAdaptiveRange](-selective-adaptive-range.html) | [jvm]<br>open fun [SelectiveAdaptiveRange](-selective-adaptive-range.html)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), desiredNeighborsCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), adjustment: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>default radius in metres |
| [SelectiveAdaptiveRange](-selective-adaptive-range.html) | [jvm]<br>open fun [SelectiveAdaptiveRange](-selective-adaptive-range.html)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), desiredNeighborsCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), molType: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>default radius in metres |


## Functions


| Name | Summary |
|---|---|
| [computeNeighborhood](../-adaptive-range/compute-neighborhood.html) | [jvm]<br>fun [computeNeighborhood](../-adaptive-range/compute-neighborhood.html)(center: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html), [P](../../it.unibo.alchemist.model/-s-a-p-e-r-e-incarnation/index.html)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.html)> |
| [isLocallyConsistent](../-abstract-locally-consistent-linking-rule/is-locally-consistent.html) | [jvm]<br>fun [isLocallyConsistent](../-abstract-locally-consistent-linking-rule/is-locally-consistent.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |


## Properties


| Name | Summary |
|---|---|
| [DEFAULT_MOLECULETYPE](-d-e-f-a-u-l-t_-m-o-l-e-c-u-l-e-t-y-p-e.html) | [jvm]<br>val [DEFAULT_MOLECULETYPE](-d-e-f-a-u-l-t_-m-o-l-e-c-u-l-e-t-y-p-e.html): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>The default filter molecule. |


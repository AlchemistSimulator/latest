//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.linkingrules](../index.md)/[SelectiveAdaptiveRange](index.md)

# SelectiveAdaptiveRange

[jvm]\
open class [SelectiveAdaptiveRange](index.md)<[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](../../it.unibo.alchemist.model.implementations.reactions/-s-a-p-e-r-e-gradient/index.md)>?> : [AdaptiveRange](../-adaptive-range/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md), [P](../../it.unibo.alchemist.model.implementations.reactions/-s-a-p-e-r-e-gradient/index.md)>

## Parameters

jvm

| | |
|---|---|
| <P> | position type |
| <T> | concentration type |

## Constructors

| | |
|---|---|
| [SelectiveAdaptiveRange](-selective-adaptive-range.md) | [jvm]<br>open fun [SelectiveAdaptiveRange](-selective-adaptive-range.md)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), minrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maxrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), desiredNeighborsCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>default radius in metres |
| [SelectiveAdaptiveRange](-selective-adaptive-range.md) | [jvm]<br>open fun [SelectiveAdaptiveRange](-selective-adaptive-range.md)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), minrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maxrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), desiredNeighborsCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), adjustment: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>default radius in metres |
| [SelectiveAdaptiveRange](-selective-adaptive-range.md) | [jvm]<br>open fun [SelectiveAdaptiveRange](-selective-adaptive-range.md)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), minrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maxrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), desiredNeighborsCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), adjustment: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), molType: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>default radius in metres |
| [SelectiveAdaptiveRange](-selective-adaptive-range.md) | [jvm]<br>open fun [SelectiveAdaptiveRange](-selective-adaptive-range.md)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), minrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), desiredNeighborsCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>default radius in metres |
| [SelectiveAdaptiveRange](-selective-adaptive-range.md) | [jvm]<br>open fun [SelectiveAdaptiveRange](-selective-adaptive-range.md)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), minrange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), desiredNeighborsCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), adjustment: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>default radius in metres |
| [SelectiveAdaptiveRange](-selective-adaptive-range.md) | [jvm]<br>open fun [SelectiveAdaptiveRange](-selective-adaptive-range.md)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), desiredNeighborsCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>default radius in metres |
| [SelectiveAdaptiveRange](-selective-adaptive-range.md) | [jvm]<br>open fun [SelectiveAdaptiveRange](-selective-adaptive-range.md)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), desiredNeighborsCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), adjustment: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>default radius in metres |
| [SelectiveAdaptiveRange](-selective-adaptive-range.md) | [jvm]<br>open fun [SelectiveAdaptiveRange](-selective-adaptive-range.md)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), desiredNeighborsCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), tolerance: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), molType: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>default radius in metres |

## Functions

| Name | Summary |
|---|---|
| [computeNeighborhood](../-adaptive-range/compute-neighborhood.md) | [jvm]<br>fun [computeNeighborhood](../-adaptive-range/compute-neighborhood.md)(center: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md), [P](../../it.unibo.alchemist.model.implementations.reactions/-s-a-p-e-r-e-gradient/index.md)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)> |
| [isLocallyConsistent](../-abstract-locally-consistent-linking-rule/is-locally-consistent.md) | [jvm]<br>fun [isLocallyConsistent](../-abstract-locally-consistent-linking-rule/is-locally-consistent.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

## Properties

| Name | Summary |
|---|---|
| [DEFAULT_MOLECULETYPE](-d-e-f-a-u-l-t_-m-o-l-e-c-u-l-e-t-y-p-e.md) | [jvm]<br>val [DEFAULT_MOLECULETYPE](-d-e-f-a-u-l-t_-m-o-l-e-c-u-l-e-t-y-p-e.md): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>The default filter molecule. |

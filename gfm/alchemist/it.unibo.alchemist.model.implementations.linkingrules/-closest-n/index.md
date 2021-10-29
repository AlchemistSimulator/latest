//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.linkingrules](../index.md)/[ClosestN](index.md)

# ClosestN

[jvm]\
open class [ClosestN](index.md)<[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)>?> : [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md), [P](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)> 

Non local-consistent rule that connect the closest N nodes together. Two nodes get connected if either one belongs to the set of the ten devices closest to the other.

## Parameters

jvm

| | |
|---|---|
| <T> | Concentration type |
| <P> | [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md) type |

## Constructors

| | |
|---|---|
| [ClosestN](-closest-n.md) | [jvm]<br>open fun [ClosestN](-closest-n.md)(n: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), expectedNodes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), maxNodes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>neighbors |
| [ClosestN](-closest-n.md) | [jvm]<br>open fun [ClosestN](-closest-n.md)(n: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), expectedNodes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>neighbors |
| [ClosestN](-closest-n.md) | [jvm]<br>open fun [ClosestN](-closest-n.md)(n: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>neighbors |

## Functions

| Name | Summary |
|---|---|
| [computeNeighborhood](compute-neighborhood.md) | [jvm]<br>fun [computeNeighborhood](compute-neighborhood.md)(center: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md), [P](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)> |
| [isLocallyConsistent](is-locally-consistent.md) | [jvm]<br>fun [isLocallyConsistent](is-locally-consistent.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

## Inheritors

| Name |
|---|
| [ConditionalClosestN](../-conditional-closest-n/index.md) |

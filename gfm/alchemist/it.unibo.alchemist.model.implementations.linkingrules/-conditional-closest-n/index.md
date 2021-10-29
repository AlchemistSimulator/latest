//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.linkingrules](../index.md)/[ConditionalClosestN](index.md)

# ConditionalClosestN

[jvm]\
class [ConditionalClosestN](index.md)<[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](../../it.unibo.alchemist.model.interfaces/-route/index.md)>?> : [ClosestN](../-closest-n/index.md)<[T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md), [P](../../it.unibo.alchemist.model.interfaces/-route/index.md)> 

A [ClosestN](../-closest-n/index.md) rule that also checks that a [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md) has a specific concentration before allowing the connection.

## Parameters

jvm

| | |
|---|---|
| <T> | Concentration type |
| <P> | [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md) type |

## Constructors

| | |
|---|---|
| [ConditionalClosestN](-conditional-closest-n.md) | [jvm]<br>open fun [ConditionalClosestN](-conditional-closest-n.md)(n: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), expectedNodes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), mol: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), value: [T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md))<br>number of neighbors |
| [ConditionalClosestN](-conditional-closest-n.md) | [jvm]<br>open fun [ConditionalClosestN](-conditional-closest-n.md)(n: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), mol: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), value: [T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md))<br>number of neighbors |

## Functions

| Name | Summary |
|---|---|
| [computeNeighborhood](../-closest-n/compute-neighborhood.md) | [jvm]<br>fun [computeNeighborhood](../-closest-n/compute-neighborhood.md)(center: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md), [P](../../it.unibo.alchemist.model.interfaces/-route/index.md)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.md)<[T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md)><br>abstract fun [computeNeighborhood](../../it.unibo.alchemist.model.interfaces/-linking-rule/compute-neighborhood.md)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md)>, p1: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md), [P](../../it.unibo.alchemist.model.interfaces/-route/index.md)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.md)<[T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md)> |
| [isLocallyConsistent](../-closest-n/is-locally-consistent.md) | [jvm]<br>fun [isLocallyConsistent](../-closest-n/is-locally-consistent.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>abstract fun [isLocallyConsistent](../../it.unibo.alchemist.model.interfaces/-linking-rule/is-locally-consistent.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

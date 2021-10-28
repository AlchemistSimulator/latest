//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.linkingrules](../index.md)/[FullyConnected](index.md)

# FullyConnected

[jvm]\
class [FullyConnected](index.md)<[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>> : [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.md)<[T](index.md), [P](index.md)> 

This rule connects each and every node to each and every other.

## Constructors

| | |
|---|---|
| [FullyConnected](-fully-connected.md) | [jvm]<br>fun [FullyConnected](-fully-connected.md)() |

## Functions

| Name | Summary |
|---|---|
| [computeNeighborhood](compute-neighborhood.md) | [jvm]<br>open override fun [computeNeighborhood](compute-neighborhood.md)(center: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [P](index.md)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.md)<[T](index.md)> |
| [isLocallyConsistent](is-locally-consistent.md) | [jvm]<br>open override fun [isLocallyConsistent](is-locally-consistent.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

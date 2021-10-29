//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.linkingrules](../index.md)/[LinkNodesWithinRoutingRange](index.md)

# LinkNodesWithinRoutingRange

[jvm]\
class [LinkNodesWithinRoutingRange](index.md)<[T](index.md)> : [AbstractLocallyConsistentLinkingRule](../-abstract-locally-consistent-linking-rule/index.md)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)>

## Parameters

jvm

| | |
|---|---|
| <T> | concentration type |

## Constructors

| | |
|---|---|
| [LinkNodesWithinRoutingRange](-link-nodes-within-routing-range.md) | [jvm]<br>open fun [LinkNodesWithinRoutingRange](-link-nodes-within-routing-range.md)(r: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>range |

## Functions

| Name | Summary |
|---|---|
| [computeNeighborhood](compute-neighborhood.md) | [jvm]<br>open fun [computeNeighborhood](compute-neighborhood.md)(center: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.md)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)> |
| [isLocallyConsistent](../-abstract-locally-consistent-linking-rule/is-locally-consistent.md) | [jvm]<br>fun [isLocallyConsistent](../-abstract-locally-consistent-linking-rule/is-locally-consistent.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

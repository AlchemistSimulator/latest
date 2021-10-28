//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.linkingrules](../index.md)/[AbstractLocallyConsistentLinkingRule](index.md)

# AbstractLocallyConsistentLinkingRule

[jvm]\
abstract class [AbstractLocallyConsistentLinkingRule](index.md)<[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<out [P](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-constant-speed/index.md)>?> : [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md), [P](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-constant-speed/index.md)>

## Parameters

jvm

| | |
|---|---|
| <T> | Concentration type |
| <P> | [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md) type |

## Functions

| Name | Summary |
|---|---|
| [computeNeighborhood](../../it.unibo.alchemist.model.interfaces/-linking-rule/compute-neighborhood.md) | [jvm]<br>abstract fun [computeNeighborhood](../../it.unibo.alchemist.model.interfaces/-linking-rule/compute-neighborhood.md)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)>, p1: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md), [P](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-constant-speed/index.md)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)> |
| [isLocallyConsistent](is-locally-consistent.md) | [jvm]<br>fun [isLocallyConsistent](is-locally-consistent.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

## Inheritors

| Name |
|---|
| [NoLinks](../-no-links/index.md) |
| [ConnectWithinDistance](../-connect-within-distance/index.md) |
| [LinkNodesWithinRoutingRange](../-link-nodes-within-routing-range/index.md) |

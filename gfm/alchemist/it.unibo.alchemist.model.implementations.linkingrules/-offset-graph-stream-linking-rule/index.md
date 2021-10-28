//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.linkingrules](../index.md)/[OffsetGraphStreamLinkingRule](index.md)

# OffsetGraphStreamLinkingRule

[jvm]\
class [OffsetGraphStreamLinkingRule](index.md)<[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>>(**offset**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **graph**: Graph) : [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.md)<[T](index.md), [P](index.md)> 

A [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.md) that statically connects nodes as they were configured by GraphStream. An [offset](offset.md) is used to determine the id of the environment's nodes when compared to the one of the provided [graph](graph.md).

## Constructors

| | |
|---|---|
| [OffsetGraphStreamLinkingRule](-offset-graph-stream-linking-rule.md) | [jvm]<br>fun [OffsetGraphStreamLinkingRule](-offset-graph-stream-linking-rule.md)(offset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), graph: Graph) |

## Functions

| Name | Summary |
|---|---|
| [computeNeighborhood](compute-neighborhood.md) | [jvm]<br>open override fun [computeNeighborhood](compute-neighborhood.md)(center: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [P](index.md)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.md)<[T](index.md)> |
| [isLocallyConsistent](is-locally-consistent.md) | [jvm]<br>open override fun [isLocallyConsistent](is-locally-consistent.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

## Properties

| Name | Summary |
|---|---|
| [graph](graph.md) | [jvm]<br>val [graph](graph.md): Graph |
| [offset](offset.md) | [jvm]<br>val [offset](offset.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

---
title: OffsetGraphStreamLinkingRule
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.linkingrules](../index.html)/[OffsetGraphStreamLinkingRule](index.html)



# OffsetGraphStreamLinkingRule



[jvm]\
class [OffsetGraphStreamLinkingRule](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>>(**offset**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **graph**: Graph) : [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.html)<[T](index.html), [P](index.html)> 

A [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.html) that statically connects nodes as they were configured by GraphStream. An [offset](offset.html) is used to determine the id of the environment's nodes when compared to the one of the provided [graph](graph.html).



## Constructors


| | |
|---|---|
| [OffsetGraphStreamLinkingRule](-offset-graph-stream-linking-rule.html) | [jvm]<br>fun [OffsetGraphStreamLinkingRule](-offset-graph-stream-linking-rule.html)(offset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), graph: Graph) |


## Functions


| Name | Summary |
|---|---|
| [computeNeighborhood](compute-neighborhood.html) | [jvm]<br>open override fun [computeNeighborhood](compute-neighborhood.html)(center: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](index.html)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.html)<[T](index.html)> |
| [isLocallyConsistent](is-locally-consistent.html) | [jvm]<br>open override fun [isLocallyConsistent](is-locally-consistent.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |


## Properties


| Name | Summary |
|---|---|
| [graph](graph.html) | [jvm]<br>val [graph](graph.html): Graph |
| [offset](offset.html) | [jvm]<br>val [offset](offset.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |


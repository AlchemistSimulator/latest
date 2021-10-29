---
title: LinkingRule
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[LinkingRule](index.html)



# LinkingRule



[jvm]\
interface [LinkingRule](index.html)<[T](index.html), [P](index.html) : [Position](../-position/index.html)<out [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

An interface that represent an auto-linking logic for nodes within an environment.



## Parameters


jvm

| | |
|---|---|
| <T> | The type which describes the concentration of a molecule |
| <P> | The position type |



## Functions


| Name | Summary |
|---|---|
| [computeNeighborhood](compute-neighborhood.html) | [jvm]<br>abstract fun [computeNeighborhood](compute-neighborhood.html)(center: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, environment: [Environment](../-environment/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>): [Neighborhood](../-neighborhood/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)><br>Produces a new neighborhood for specified node considering its position. |
| [isLocallyConsistent](is-locally-consistent.html) | [jvm]<br>abstract fun [isLocallyConsistent](is-locally-consistent.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Some rules may require to be evaluated against multiple nodes until the situations gets consistent. |


## Inheritors


| Name |
|---|
| [ClosestN](../../it.unibo.alchemist.model.implementations.linkingrules/-closest-n/index.html) |
| [AbstractLocallyConsistentLinkingRule](../../it.unibo.alchemist.model.implementations.linkingrules/-abstract-locally-consistent-linking-rule/index.html) |
| [FullyConnected](../../it.unibo.alchemist.model.implementations.linkingrules/-fully-connected/index.html) |
| [CombinedLinkingRule](../../it.unibo.alchemist.model.implementations.linkingrules/-combined-linking-rule/index.html) |
| [OffsetGraphStreamLinkingRule](../../it.unibo.alchemist.model.implementations.linkingrules/-offset-graph-stream-linking-rule/index.html) |


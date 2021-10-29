//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[LinkingRule](index.md)

# LinkingRule

[jvm]\
interface [LinkingRule](index.md)<[T](index.md), [P](index.md) : [Position](../-position/index.md)<out [P](../-incarnation/index.md)>?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

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
| [computeNeighborhood](compute-neighborhood.md) | [jvm]<br>abstract fun [computeNeighborhood](compute-neighborhood.md)(center: [Node](../-node/index.md)<[T](../-node/index.md)>, environment: [Environment](../-environment/index.md)<[T](../-node/index.md), [P](../-incarnation/index.md)>): [Neighborhood](../-neighborhood/index.md)<[T](../-node/index.md)><br>Produces a new neighborhood for specified node considering its position. |
| [isLocallyConsistent](is-locally-consistent.md) | [jvm]<br>abstract fun [isLocallyConsistent](is-locally-consistent.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Some rules may require to be evaluated against multiple nodes until the situations gets consistent. |

## Inheritors

| Name |
|---|
| [ClosestN](../../it.unibo.alchemist.model.implementations.linkingrules/-closest-n/index.md) |
| [AbstractLocallyConsistentLinkingRule](../../it.unibo.alchemist.model.implementations.linkingrules/-abstract-locally-consistent-linking-rule/index.md) |
| [FullyConnected](../../it.unibo.alchemist.model.implementations.linkingrules/-fully-connected/index.md) |
| [CombinedLinkingRule](../../it.unibo.alchemist.model.implementations.linkingrules/-combined-linking-rule/index.md) |
| [OffsetGraphStreamLinkingRule](../../it.unibo.alchemist.model.implementations.linkingrules/-offset-graph-stream-linking-rule/index.md) |

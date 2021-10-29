//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Environment](index.md)/[getNodesWithinRange](get-nodes-within-range.md)

# getNodesWithinRange

[jvm]\
abstract fun [getNodesWithinRange](get-nodes-within-range.md)(center: [Node](../-node/index.md)<[T](../-node/index.md)>, range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): ListSet<[Node](../-node/index.md)<[T](../-node/index.md)>>

Given a node (center) this method returns a list of all the surroundings nodes within the given range. Note that this method (depending on the implementation) might be not optimized and it's consequently **much** better to use [getNeighborhood](get-neighborhood.md) and filter the neighborhood if you are sure that all the nodes within the range are connected to the center.

#### Return

the list of nodes within the range

## Parameters

jvm

| | |
|---|---|
| center | the node to consider as center |
| range | the exploration range |

[jvm]\
abstract fun [getNodesWithinRange](get-nodes-within-range.md)(center: [P](../-incarnation/index.md), range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): ListSet<[Node](../-node/index.md)<[T](../-node/index.md)>>

Given a [Position](../-position/index.md)(center) this method returns a list of all the surroundings nodes within the given range. Note that this method (depending on the implementation) might be not optimized.

#### Return

the list of nodes within the range

## Parameters

jvm

| | |
|---|---|
| center | the [Position](../-position/index.md) to consider as center |
| range | the exploration range |

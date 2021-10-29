---
title: getNodesWithinRange
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Environment](index.html)/[getNodesWithinRange](get-nodes-within-range.html)



# getNodesWithinRange



[jvm]\
abstract fun [getNodesWithinRange](get-nodes-within-range.html)(center: [Node](../-node/index.html)<[T](../-node/index.html)>, range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): ListSet<[Node](../-node/index.html)<[T](../-node/index.html)>>



Given a node (center) this method returns a list of all the surroundings nodes within the given range. Note that this method (depending on the implementation) might be not optimized and it's consequently **much** better to use [getNeighborhood](get-neighborhood.html) and filter the neighborhood if you are sure that all the nodes within the range are connected to the center.



#### Return



the list of nodes within the range



## Parameters


jvm

| | |
|---|---|
| center | the node to consider as center |
| range | the exploration range |





[jvm]\
abstract fun [getNodesWithinRange](get-nodes-within-range.html)(center: [P](../-position2-d/index.html), range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): ListSet<[Node](../-node/index.html)<[T](../-node/index.html)>>



Given a [Position](../-position/index.html)(center) this method returns a list of all the surroundings nodes within the given range. Note that this method (depending on the implementation) might be not optimized.



#### Return



the list of nodes within the range



## Parameters


jvm

| | |
|---|---|
| center | the [Position](../-position/index.html) to consider as center |
| range | the exploration range |





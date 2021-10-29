---
title: farthestPositionReachable
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.environments](../index.html)/[Continuous2DEnvironment](index.html)/[farthestPositionReachable](farthest-position-reachable.html)



# farthestPositionReachable



[jvm]\
open override fun [farthestPositionReachable](farthest-position-reachable.html)(node: [NodeWithShape](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html)<[T](index.html), *, *>, desiredPosition: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), hitboxRadius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)



[node](farthest-position-reachable.html).canFit must be true for the returned position. For a better understanding of how to compute collision points with circular hitboxes see [this discussion](https://bit.ly/3f00NvJ).





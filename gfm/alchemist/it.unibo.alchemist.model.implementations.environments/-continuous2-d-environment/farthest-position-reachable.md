//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.environments](../index.md)/[Continuous2DEnvironment](index.md)/[farthestPositionReachable](farthest-position-reachable.md)

# farthestPositionReachable

[jvm]\
open override fun [farthestPositionReachable](farthest-position-reachable.md)(node: [NodeWithShape](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md)<[T](index.md), *, *>, desiredPosition: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), hitboxRadius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)

[node](farthest-position-reachable.md).canFit must be true for the returned position. For a better understanding of how to compute collision points with circular hitboxes see [this discussion](https://bit.ly/3f00NvJ).

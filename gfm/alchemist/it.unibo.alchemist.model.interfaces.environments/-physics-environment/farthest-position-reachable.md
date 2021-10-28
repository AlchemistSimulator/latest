//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces.environments](../index.md)/[PhysicsEnvironment](index.md)/[farthestPositionReachable](farthest-position-reachable.md)

# farthestPositionReachable

[jvm]\
abstract fun [farthestPositionReachable](farthest-position-reachable.md)(node: [NodeWithShape](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md)<[T](index.md), *, *>, desiredPosition: [P](index.md), hitboxRadius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = node.shape.radius): [P](index.md)

Computes the farthest position reachable by a [node](farthest-position-reachable.md) towards a [desiredPosition](farthest-position-reachable.md), avoiding node overlapping. If no node is located in between, [desiredPosition](farthest-position-reachable.md) is returned. Otherwise, the first position where the node collides with someone else is returned. For collision purposes, hitboxes are used: each node is given a circular hitbox of radius equal to its shape's radius (shapeless nodes can't cause overlapping). The client can specify a different radius for the hitbox of the moving node.

---
title: farthestPositionReachable
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces.environments](../index.html)/[PhysicsEnvironment](index.html)/[farthestPositionReachable](farthest-position-reachable.html)



# farthestPositionReachable



[jvm]\
abstract fun [farthestPositionReachable](farthest-position-reachable.html)(node: [NodeWithShape](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html)<[T](index.html), *, *>, desiredPosition: [P](index.html), hitboxRadius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = node.shape.radius): [P](index.html)



Computes the farthest position reachable by a [node](farthest-position-reachable.html) towards a [desiredPosition](farthest-position-reachable.html), avoiding node overlapping. If no node is located in between, [desiredPosition](farthest-position-reachable.html) is returned. Otherwise, the first position where the node collides with someone else is returned. For collision purposes, hitboxes are used: each node is given a circular hitbox of radius equal to its shape's radius (shapeless nodes can't cause overlapping). The client can specify a different radius for the hitbox of the moving node.





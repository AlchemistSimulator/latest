//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[EuclideanEnvironment](index.md)/[moveNode](move-node.md)

# moveNode

[jvm]\
open fun [moveNode](move-node.md)(node: [Node](../-node/index.md)<[T](index.md)>, direction: [P](index.md))

This method moves a [node](move-node.md) in the environment toward some [direction](move-node.md). If node move is unsupported, it does nothing. Subclasses may override this method if they want to change the way a node moves towards some direction. The current implementation internally calls {@link #moveNodeToPosition(Node, Position2D)}, as such, overriding that method may suffice.

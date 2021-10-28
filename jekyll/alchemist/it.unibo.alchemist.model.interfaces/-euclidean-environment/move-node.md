---
title: moveNode
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[EuclideanEnvironment](index.html)/[moveNode](move-node.html)



# moveNode



[jvm]\
open fun [moveNode](move-node.html)(node: [Node](../-node/index.html)<[T](index.html)>, direction: [P](index.html))



This method moves a [node](move-node.html) in the environment toward some [direction](move-node.html). If node move is unsupported, it does nothing. Subclasses may override this method if they want to change the way a node moves towards some direction. The current implementation internally calls {@link #moveNodeToPosition(Node, Position2D)}, as such, overriding that method may suffice.





---
title: getNodesWithin
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces.environments](../index.html)/[PhysicsEnvironment](index.html)/[getNodesWithin](get-nodes-within.html)



# getNodesWithin



[jvm]\
abstract fun [getNodesWithin](get-nodes-within.html)(shape: [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.html)<[P](index.html), [A](index.html)>): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>>



Gets all nodes whose shape.intersect is true for the given shape.



#### Return



the set of nodes colliding with the given shape



## Parameters


jvm

| | |
|---|---|
| shape | the shape |





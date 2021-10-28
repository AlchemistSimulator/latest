//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces.environments](../index.md)/[PhysicsEnvironment](index.md)/[getNodesWithin](get-nodes-within.md)

# getNodesWithin

[jvm]\
abstract fun [getNodesWithin](get-nodes-within.md)(shape: [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.md)<[P](index.md), [A](index.md)>): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>>

Gets all nodes whose shape.intersect is true for the given shape.

#### Return

the set of nodes colliding with the given shape

## Parameters

jvm

| | |
|---|---|
| shape | the shape |

---
title: AbstractOrientingPedestrian
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.nodes](../index.html)/[AbstractOrientingPedestrian](index.html)/[AbstractOrientingPedestrian](-abstract-orienting-pedestrian.html)



# AbstractOrientingPedestrian



[jvm]\
fun <[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[P](index.html)>, [N](index.html) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[P](index.html), [A](index.html)>, [E](index.html), [F](index.html) : [GeometricShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/index.html)<[P](index.html), [A](index.html)>> [AbstractOrientingPedestrian](-abstract-orienting-pedestrian.html)(knowledgeDegree: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), randomGenerator: RandomGenerator, environment: [PhysicsEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html)<*, [T](index.html), [P](index.html), [A](index.html), [N](index.html), [E](index.html), [F](index.html)>, group: [PedestrianGroup](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.html)<[T](index.html), [P](index.html), [A](index.html)>? = null, minArea: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 10.0)



## Parameters


jvm

| | |
|---|---|
| T | the concentration type. |
| P | the [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html) type and [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html) type for the space this pedestrian is inside. |
| A | the transformations supported by the shapes in this space. |
| L | the type of landmarks in the pedestrian's [cognitiveMap](cognitive-map.html). |
| N | the type of nodes of the navigation graph provided by the environment. |
| E | the type of edges of the navigation graph provided by the environment. |
| F | the type of the shape factory provided by the environment. |





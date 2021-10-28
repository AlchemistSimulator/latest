//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.nodes](../index.md)/[AbstractOrientingPedestrian](index.md)/[AbstractOrientingPedestrian](-abstract-orienting-pedestrian.md)

# AbstractOrientingPedestrian

[jvm]\
fun <[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[P](index.md)>, [N](index.md) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.md)<[P](index.md), [A](index.md)>, [E](index.md), [F](index.md) : [GeometricShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/index.md)<[P](index.md), [A](index.md)>> [AbstractOrientingPedestrian](-abstract-orienting-pedestrian.md)(knowledgeDegree: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), randomGenerator: RandomGenerator, environment: [PhysicsEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md)<*, [T](index.md), [P](index.md), [A](index.md), [N](index.md), [E](index.md), [F](index.md)>, group: [PedestrianGroup](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.md)<[T](index.md), [P](index.md), [A](index.md)>? = null, minArea: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 10.0)

## Parameters

jvm

| | |
|---|---|
| T | the concentration type. |
| P | the [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md) type and [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md) type for the space this pedestrian is inside. |
| A | the transformations supported by the shapes in this space. |
| L | the type of landmarks in the pedestrian's [cognitiveMap](cognitive-map.md). |
| N | the type of nodes of the navigation graph provided by the environment. |
| E | the type of edges of the navigation graph provided by the environment. |
| F | the type of the shape factory provided by the environment. |

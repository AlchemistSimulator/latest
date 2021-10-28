//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.nodes](../index.md)/[HomogeneousOrientingPedestrian2D](index.md)/[HomogeneousOrientingPedestrian2D](-homogeneous-orienting-pedestrian2-d.md)

# HomogeneousOrientingPedestrian2D

[jvm]\

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()

fun <[T](index.md), [N](index.md) : [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), [E](index.md)> [HomogeneousOrientingPedestrian2D](-homogeneous-orienting-pedestrian2-d.md)(environment: [EuclideanPhysics2DEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-euclidean-physics2-d-environment-with-graph/index.md)<*, [T](index.md), [N](index.md), [E](index.md)>, randomGenerator: RandomGenerator, knowledgeDegree: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), minSide: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 30.0, maxSide: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 60.0, group: [PedestrianGroup2D](../../it.unibo.alchemist.model.interfaces/-pedestrian-group2-d/index.md)<[T](index.md)>? = null)

## Parameters

jvm

| | |
|---|---|
| T | the concentration type. |
| N | the type of nodes of the navigation graph provided by the environment. |
| E | the type of edges of the navigation graph provided by the environment. |

//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.reactions](../index.md)/[NavigationPrioritisedSteering](index.md)/[NavigationPrioritisedSteering](-navigation-prioritised-steering.md)

# NavigationPrioritisedSteering

[jvm]\

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()

fun <[T](index.md), [N](index.md) : [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md)> [NavigationPrioritisedSteering](-navigation-prioritised-steering.md)(env: [Euclidean2DEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment-with-graph/index.md)<*, [T](index.md), [N](index.md), *>, pedestrian: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.md)<[T](index.md)>, timeDistribution: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.md)<[T](index.md)>, toleranceAngle: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = Math.toDegrees(SinglePrevalent.DEFAULT_TOLERANCE_ANGLE), alpha: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = SinglePrevalent.DEFAULT_ALPHA)

## Parameters

jvm

| | |
|---|---|
| T | concentration type |
| N | type of nodes of the environment's graph. |

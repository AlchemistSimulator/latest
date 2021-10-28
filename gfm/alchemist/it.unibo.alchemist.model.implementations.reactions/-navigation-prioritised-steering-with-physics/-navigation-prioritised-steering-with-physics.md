//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.reactions](../index.md)/[NavigationPrioritisedSteeringWithPhysics](index.md)/[NavigationPrioritisedSteeringWithPhysics](-navigation-prioritised-steering-with-physics.md)

# NavigationPrioritisedSteeringWithPhysics

[jvm]\

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()

fun <[T](index.md), [N](index.md) : [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md)> [NavigationPrioritisedSteeringWithPhysics](-navigation-prioritised-steering-with-physics.md)(env: [EuclideanPhysics2DEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-euclidean-physics2-d-environment-with-graph/index.md)<*, [T](index.md), [N](index.md), *>, pedestrian: [PhysicalPedestrian2D](../../it.unibo.alchemist.model.interfaces/-physical-pedestrian2-d/index.md)<[T](index.md)>, timeDistribution: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.md)<[T](index.md)>, toleranceAngle: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = Math.toDegrees(SinglePrevalent.DEFAULT_TOLERANCE_ANGLE), alpha: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = SinglePrevalent.DEFAULT_ALPHA)

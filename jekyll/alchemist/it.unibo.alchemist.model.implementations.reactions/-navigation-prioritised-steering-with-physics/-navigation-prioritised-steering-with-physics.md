---
title: NavigationPrioritisedSteeringWithPhysics
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.reactions](../index.html)/[NavigationPrioritisedSteeringWithPhysics](index.html)/[NavigationPrioritisedSteeringWithPhysics](-navigation-prioritised-steering-with-physics.html)



# NavigationPrioritisedSteeringWithPhysics



[jvm]\




@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()



fun <[T](index.html), [N](index.html) : [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html)> [NavigationPrioritisedSteeringWithPhysics](-navigation-prioritised-steering-with-physics.html)(env: [EuclideanPhysics2DEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-euclidean-physics2-d-environment-with-graph/index.html)<*, [T](index.html), [N](index.html), *>, pedestrian: [PhysicalPedestrian2D](../../it.unibo.alchemist.model.interfaces/-physical-pedestrian2-d/index.html)<[T](index.html)>, timeDistribution: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](index.html)>, toleranceAngle: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = Math.toDegrees(SinglePrevalent.DEFAULT_TOLERANCE_ANGLE), alpha: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = SinglePrevalent.DEFAULT_ALPHA)





---
title: SinglePrevalent
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions.steeringstrategies](../index.html)/[SinglePrevalent](index.html)/[SinglePrevalent](-single-prevalent.html)



# SinglePrevalent



[jvm]\
fun <[T](index.html), [N](index.html) : [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html)> [SinglePrevalent](-single-prevalent.html)(environment: [Euclidean2DEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment-with-graph/index.html)<*, [T](index.html), [N](index.html), *>, pedestrian: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.html)<[T](index.html)>, prevalent: SteeringActions<[T](index.html)>.() -> [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.html#-517309547%2FClasslikes%2F-134779887)<[T](index.html), *, *, [N](index.html), *>, toleranceAngle: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = DEFAULT_TOLERANCE_ANGLE, alpha: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = DEFAULT_ALPHA, maxWalk: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maxWalkRatio: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = DEFAULT_MAX_WALK_RATIO, delta: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = DEFAULT_DELTA)



## Parameters


jvm

| | |
|---|---|
| T | concentration type |
| N | type of nodes of the environment's graph. |





//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions.steeringstrategies](../index.md)/[SinglePrevalent](index.md)/[SinglePrevalent](-single-prevalent.md)

# SinglePrevalent

[jvm]\
fun <[T](index.md), [N](index.md) : [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md)> [SinglePrevalent](-single-prevalent.md)(environment: [Euclidean2DEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment-with-graph/index.md)<*, [T](index.md), [N](index.md), *>, pedestrian: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.md)<[T](index.md)>, prevalent: SteeringActions<[T](index.md)>.() -> [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.md#-517309547%2FClasslikes%2F-267951372)<[T](index.md), *, *, [N](index.md), *>, toleranceAngle: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = DEFAULT_TOLERANCE_ANGLE, alpha: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = DEFAULT_ALPHA, maxWalk: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maxWalkRatio: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = DEFAULT_MAX_WALK_RATIO, delta: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = DEFAULT_DELTA)

## Parameters

jvm

| | |
|---|---|
| T | concentration type |
| N | type of nodes of the environment's graph. |

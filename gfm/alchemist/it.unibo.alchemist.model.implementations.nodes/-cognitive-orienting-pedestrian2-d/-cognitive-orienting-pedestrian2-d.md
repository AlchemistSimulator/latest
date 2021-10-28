//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.nodes](../index.md)/[CognitiveOrientingPedestrian2D](index.md)/[CognitiveOrientingPedestrian2D](-cognitive-orienting-pedestrian2-d.md)

# CognitiveOrientingPedestrian2D

[jvm]\

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()

fun <[T](index.md), [N](index.md) : [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), [E](index.md)> [CognitiveOrientingPedestrian2D](-cognitive-orienting-pedestrian2-d.md)(environment: [EuclideanPhysics2DEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-euclidean-physics2-d-environment-with-graph/index.md)<*, [T](index.md), [N](index.md), [E](index.md)>, randomGenerator: RandomGenerator, knowledgeDegree: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), group: [PedestrianGroup2D](../../it.unibo.alchemist.model.interfaces/-pedestrian-group2-d/index.md)<[T](index.md)>? = null, age: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), gender: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), danger: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)? = null)

Allows to specify age and gender with a string.

[jvm]\

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()

fun <[T](index.md), [N](index.md) : [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), [E](index.md)> [CognitiveOrientingPedestrian2D](-cognitive-orienting-pedestrian2-d.md)(environment: [EuclideanPhysics2DEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-euclidean-physics2-d-environment-with-graph/index.md)<*, [T](index.md), [N](index.md), [E](index.md)>, randomGenerator: RandomGenerator, knowledgeDegree: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), group: [PedestrianGroup2D](../../it.unibo.alchemist.model.interfaces/-pedestrian-group2-d/index.md)<[T](index.md)>? = null, age: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), gender: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), danger: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)? = null)

Allows to specify age with an int and gender with a string.

[jvm]\

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()

fun <[T](index.md), [N](index.md) : [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), [E](index.md)> [CognitiveOrientingPedestrian2D](-cognitive-orienting-pedestrian2-d.md)(environment: [EuclideanPhysics2DEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-euclidean-physics2-d-environment-with-graph/index.md)<*, [T](index.md), [N](index.md), [E](index.md)>, randomGenerator: RandomGenerator, knowledgeDegree: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), group: [PedestrianGroup2D](../../it.unibo.alchemist.model.interfaces/-pedestrian-group2-d/index.md)<[T](index.md)>? = null, age: [Age](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-age/index.md), gender: [Gender](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-gender/index.md), danger: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)? = null, consciousness: [CognitivePedestrian2D](../-cognitive-pedestrian2-d/index.md)<[T](index.md)> = CognitivePedestrian2D(environment, randomGenerator, age, gender, danger, group))

## Parameters

jvm

| | |
|---|---|
| T | the concentration type. |
| N | the type of nodes of the navigation graph provided by the environment. |
| E | the type of edges of the navigation graph provided by the environment. |

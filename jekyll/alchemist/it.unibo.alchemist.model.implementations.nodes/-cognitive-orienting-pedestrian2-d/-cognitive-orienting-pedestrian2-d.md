---
title: CognitiveOrientingPedestrian2D
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.nodes](../index.html)/[CognitiveOrientingPedestrian2D](index.html)/[CognitiveOrientingPedestrian2D](-cognitive-orienting-pedestrian2-d.html)



# CognitiveOrientingPedestrian2D



[jvm]\




@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()



fun <[T](index.html), [N](index.html) : [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), [E](index.html)> [CognitiveOrientingPedestrian2D](-cognitive-orienting-pedestrian2-d.html)(environment: [EuclideanPhysics2DEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-euclidean-physics2-d-environment-with-graph/index.html)<*, [T](index.html), [N](index.html), [E](index.html)>, randomGenerator: RandomGenerator, knowledgeDegree: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), group: [PedestrianGroup2D](../../it.unibo.alchemist.model.interfaces/-pedestrian-group2-d/index.html)<[T](index.html)>? = null, age: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), gender: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), danger: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)? = null)



Allows to specify age and gender with a string.





[jvm]\




@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()



fun <[T](index.html), [N](index.html) : [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), [E](index.html)> [CognitiveOrientingPedestrian2D](-cognitive-orienting-pedestrian2-d.html)(environment: [EuclideanPhysics2DEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-euclidean-physics2-d-environment-with-graph/index.html)<*, [T](index.html), [N](index.html), [E](index.html)>, randomGenerator: RandomGenerator, knowledgeDegree: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), group: [PedestrianGroup2D](../../it.unibo.alchemist.model.interfaces/-pedestrian-group2-d/index.html)<[T](index.html)>? = null, age: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), gender: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), danger: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)? = null)



Allows to specify age with an int and gender with a string.





[jvm]\




@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()



fun <[T](index.html), [N](index.html) : [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), [E](index.html)> [CognitiveOrientingPedestrian2D](-cognitive-orienting-pedestrian2-d.html)(environment: [EuclideanPhysics2DEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-euclidean-physics2-d-environment-with-graph/index.html)<*, [T](index.html), [N](index.html), [E](index.html)>, randomGenerator: RandomGenerator, knowledgeDegree: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), group: [PedestrianGroup2D](../../it.unibo.alchemist.model.interfaces/-pedestrian-group2-d/index.html)<[T](index.html)>? = null, age: [Age](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-age/index.html), gender: [Gender](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-gender/index.html), danger: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)? = null, consciousness: [CognitivePedestrian2D](../-cognitive-pedestrian2-d/index.html)<[T](index.html)> = CognitivePedestrian2D(environment, randomGenerator, age, gender, danger, group))



## Parameters


jvm

| | |
|---|---|
| T | the concentration type. |
| N | the type of nodes of the navigation graph provided by the environment. |
| E | the type of edges of the navigation graph provided by the environment. |





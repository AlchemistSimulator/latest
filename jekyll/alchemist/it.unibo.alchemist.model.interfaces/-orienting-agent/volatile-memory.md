---
title: volatileMemory
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[OrientingAgent](index.html)/[volatileMemory](volatile-memory.html)



# volatileMemory



[jvm]\
abstract val [volatileMemory](volatile-memory.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[V](index.html), [A](index.html)>, [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>



The volatile memory of the agent: it models the ability to remember areas of the environment already visited since the start of the simulation. Each area is paired with the number of visits. Areas are assumed to be represented as [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)s, as in [NavigationGraph](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-navigation-graph/index.html)s.





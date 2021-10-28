//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[OrientingAgent](index.md)/[volatileMemory](volatile-memory.md)

# volatileMemory

[jvm]\
abstract val [volatileMemory](volatile-memory.md): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.md)<[V](index.md), [A](index.md)>, [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>

The volatile memory of the agent: it models the ability to remember areas of the environment already visited since the start of the simulation. Each area is paired with the number of visits. Areas are assumed to be represented as [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.md)s, as in [NavigationGraph](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-navigation-graph/index.md)s.

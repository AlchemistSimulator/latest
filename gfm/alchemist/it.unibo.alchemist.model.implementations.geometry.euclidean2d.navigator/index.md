//[alchemist](../../index.md)/[it.unibo.alchemist.model.implementations.geometry.euclidean2d.navigator](index.md)

# Package it.unibo.alchemist.model.implementations.geometry.euclidean2d.navigator

## Types

| Name | Summary |
|---|---|
| [ExtendableConvexPolygonInEnvironment](-extendable-convex-polygon-in-environment/index.md) | [jvm]<br>class [ExtendableConvexPolygonInEnvironment](-extendable-convex-polygon-in-environment/index.md)(**vertices**: [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Euclidean2DPosition](../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>, **origin**: [Euclidean2DPosition](../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), **width**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **height**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **awtObstacles**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html)>) : [AwtMutableConvexPolygon](../it.unibo.alchemist.model.implementations.geometry.euclidean2d/-awt-mutable-convex-polygon/index.md), [ExtendableConvexPolygon](../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.navigator/-extendable-convex-polygon/index.md)<br>An [ExtendableConvexPolygon](../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.navigator/-extendable-convex-polygon/index.md) located inside an environment with obstacles. |

## Functions

| Name | Summary |
|---|---|
| [generateNavigationGraph](generate-navigation-graph.md) | [jvm]<br>fun [generateNavigationGraph](generate-navigation-graph.md)(origin: [Euclidean2DPosition](../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md) = Euclidean2DPosition(0.0, 0.0), width: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), height: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), obstacles: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html)>, rooms: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[Euclidean2DPosition](../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>, unity: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0): [Euclidean2DNavigationGraph](../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/index.md#-513689941%2FClasslikes%2F-267951372)<br>TODO(improve the quality of this algorithm) NaviGator (Navigation Graphs Generator) is an algorithm capable of generating an [Euclidean2DNavigationGraph](../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/index.md#-513689941%2FClasslikes%2F-267951372) of a given environment with obstacles. |
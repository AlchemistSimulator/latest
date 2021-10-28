//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.geometry.euclidean2d.navigator](../index.md)/[ExtendableConvexPolygonInEnvironment](index.md)/[polygonalObstacles](polygonal-obstacles.md)

# polygonalObstacles

[jvm]\
lateinit var [polygonalObstacles](polygonal-obstacles.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md)>

Obstacles represented as [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md)s, are assumed to be mutable but limited to the extension (i.e. they can only grow, not shrink). This is the behavior of seeds used by [generateNavigationGraph](../generate-navigation-graph.md), making this assumption allows to cache useful data such as whether an edge can still advance or an obstacle has already been encountered. This is a var but is assumed to be set only once before starting to extend this polygon.

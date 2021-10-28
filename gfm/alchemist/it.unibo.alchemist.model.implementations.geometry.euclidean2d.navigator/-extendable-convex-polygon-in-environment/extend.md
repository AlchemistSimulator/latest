//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.geometry.euclidean2d.navigator](../index.md)/[ExtendableConvexPolygonInEnvironment](index.md)/[extend](extend.md)

# extend

[jvm]\
open override fun [extend](extend.md)(step: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Extends the polygon in each direction of a quantity equal to [step](extend.md). The advancement of an edge is blocked if an obstacle is intersected, unless in a particular case called advanced case. Such case shows up when a single vertex of the polygon intruded an obstacle, but no vertex from the obstacle intruded the polygon. Plus, the intruded side of the obstacle should be oblique (or better, its slope should be different from the one of the advancing edge). When this happens, we can do a simple operation in order to keep growing and allow a higher coverage of the walkable area. We increment the order of the polygon (by adding a vertex) and adjust the direction of growth in order for the new edge to follow the side of the obstacle.

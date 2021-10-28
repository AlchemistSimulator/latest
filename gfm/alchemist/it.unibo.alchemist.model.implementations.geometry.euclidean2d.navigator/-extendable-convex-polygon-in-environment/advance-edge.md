//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.geometry.euclidean2d.navigator](../index.md)/[ExtendableConvexPolygonInEnvironment](index.md)/[advanceEdge](advance-edge.md)

# advanceEdge

[jvm]\
open override fun [advanceEdge](advance-edge.md)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), step: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Advances an edge in its normal direction of a quantity equal to [step](advance-edge.md), if [extend](extend.md) has modified the growth direction of the edge so as to follow an oblique obstacle (advanced case), the modified growth direction is used. The polygon is prevented from growing out of the environment's boundaries, but not from intersecting obstacles.

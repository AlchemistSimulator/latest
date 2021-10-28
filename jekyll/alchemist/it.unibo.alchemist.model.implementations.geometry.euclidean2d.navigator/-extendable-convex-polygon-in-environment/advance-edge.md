---
title: advanceEdge
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.geometry.euclidean2d.navigator](../index.html)/[ExtendableConvexPolygonInEnvironment](index.html)/[advanceEdge](advance-edge.html)



# advanceEdge



[jvm]\
open override fun [advanceEdge](advance-edge.html)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), step: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)



Advances an edge in its normal direction of a quantity equal to [step](advance-edge.html), if [extend](extend.html) has modified the growth direction of the edge so as to follow an oblique obstacle (advanced case), the modified growth direction is used. The polygon is prevented from growing out of the environment's boundaries, but not from intersecting obstacles.





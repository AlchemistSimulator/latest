//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d.navigator](../index.md)/[ExtendableConvexPolygon](index.md)/[advanceEdge](advance-edge.md)

# advanceEdge

[jvm]\
abstract fun [advanceEdge](advance-edge.md)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), step: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Advances an edge in its normal direction.

## Parameters

jvm

| | |
|---|---|
| index | the index of the edge to advance (edge i connects vertices i and i+1) |
| step | the length of the vector that will be used to advance the edge, negative values are supported and will shrink the polygon instead of extending it. |

//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d](../index.md)/[MutableConvexPolygon](index.md)/[replaceEdge](replace-edge.md)

# replaceEdge

[jvm]\
abstract fun [replaceEdge](replace-edge.md)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), newEdge: [Segment2D](../-segment2-d/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Replaces an edge of the polygon.

## Parameters

jvm

| | |
|---|---|
| index | the index of the edge to replace (edge i connects vertices i and i+1) |
| newEdge | the new edge |

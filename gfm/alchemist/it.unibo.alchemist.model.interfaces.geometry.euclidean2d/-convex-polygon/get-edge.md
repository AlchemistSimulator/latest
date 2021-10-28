//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d](../index.md)/[ConvexPolygon](index.md)/[getEdge](get-edge.md)

# getEdge

[jvm]\
abstract fun [getEdge](get-edge.md)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Segment2D](../-segment2-d/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>

Depending on the implementation, this may be faster than [edges](edges.md).get([index](get-edge.md)).

## Parameters

jvm

| | |
|---|---|
| index | indicates which edge to get: edge i connects vertices i and i+1 (with respect to the ordering of vertices used in [vertices](vertices.md)) |

---
title: getEdge
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d](../index.html)/[ConvexPolygon](index.html)/[getEdge](get-edge.html)



# getEdge



[jvm]\
abstract fun [getEdge](get-edge.html)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Segment2D](../-segment2-d/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>



Depending on the implementation, this may be faster than [edges](edges.html).get([index](get-edge.html)).



## Parameters


jvm

| | |
|---|---|
| index | indicates which edge to get: edge i connects vertices i and i+1 (with respect to the ordering of vertices used in [vertices](vertices.html)) |





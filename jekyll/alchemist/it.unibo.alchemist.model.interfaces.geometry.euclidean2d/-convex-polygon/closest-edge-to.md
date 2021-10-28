---
title: closestEdgeTo
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d](../index.html)/[ConvexPolygon](index.html)/[closestEdgeTo](closest-edge-to.html)



# closestEdgeTo



[jvm]\
abstract fun [closestEdgeTo](closest-edge-to.html)(segment: [Segment2D](../-segment2-d/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>): [Segment2D](../-segment2-d/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>



Finds the edge of the polygon closest to the provided [segment](closest-edge-to.html), i.e. the first one that would collide (= intersect) with the segment in case the polygon extended on each side.



## Parameters


jvm

| | |
|---|---|
| segment | the segment |





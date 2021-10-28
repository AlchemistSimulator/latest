//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.geometry.euclidean2d](../index.md)/[AbstractConvexPolygon](index.md)/[closestEdgeTo](closest-edge-to.md)

# closestEdgeTo

[jvm]\
open override fun [closestEdgeTo](closest-edge-to.md)(segment: [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>): [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>

Finds the edge of the polygon closest to the provided [segment](closest-edge-to.md), i.e. the first one that would collide (= intersect) with the segment in case the polygon extended on each side.

## Parameters

jvm

| | |
|---|---|
| segment | the segment |

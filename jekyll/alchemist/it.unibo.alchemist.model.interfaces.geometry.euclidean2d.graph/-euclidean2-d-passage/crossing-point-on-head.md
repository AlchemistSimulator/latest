---
title: crossingPointOnHead
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph](../index.html)/[Euclidean2DPassage](index.html)/[crossingPointOnHead](crossing-point-on-head.html)



# crossingPointOnHead



[jvm]\
fun [crossingPointOnHead](crossing-point-on-head.html)(crossingPointOnTail: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)



Provided the [crossingPointOnTail](crossing-point-on-head.html) that an agent has reached (or will reach), this method computes the point belonging to the boundary of [head](head.html) that the agent should point towards to cross the passage (i.e. the first point belonging to [head](head.html)'s boundary that is encountered by throwing a ray from [crossingPointOnTail](crossing-point-on-head.html) along [passageShapeOnTail](passage-shape-on-tail.html)'s normal direction). Note that the returned point may not be formally contained in [head](head.html) depending on the definition of insideness used by [ConvexPolygon.contains](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/contains.html), prefer using [ConvexPolygon.containsBoundaryIncluded](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/contains-boundary-included.html).





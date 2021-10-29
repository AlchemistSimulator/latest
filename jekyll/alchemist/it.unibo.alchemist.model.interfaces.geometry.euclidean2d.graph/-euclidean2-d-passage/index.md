---
title: Euclidean2DPassage
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph](../index.html)/[Euclidean2DPassage](index.html)



# Euclidean2DPassage



[jvm]\
data class [Euclidean2DPassage](index.html)(**tail**: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), **head**: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), **passageShapeOnTail**: [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>)

Defines a passage between two [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html)s in an euclidean bidimensional space. The passage is oriented, which means it connects [tail](tail.html) to [head](head.html), but the opposite is not necessarily true. [tail](tail.html) and [head](head.html) can be non-adjacent (there can be some distance between them), this introduces navigation issues as agents may not know which direction to follow when crossing a passage. [passageShapeOnTail](passage-shape-on-tail.html) is a [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.html) representing the shape of the passage on [tail](tail.html)'s boundary (e.g. in indoor environments, the segment should represent the shape of the door between two rooms). [passageShapeOnTail](passage-shape-on-tail.html) must be determined so as to guarantee that [head](head.html) is reachable by throwing a ray from any point of the segment in its normal direction. This solves navigation issues as it provides agents with a direction to follow when crossing [Euclidean2DPassage](index.html)s (namely, the normal direction to [passageShapeOnTail](passage-shape-on-tail.html)).



## Constructors


| | |
|---|---|
| [Euclidean2DPassage](-euclidean2-d-passage.html) | [jvm]<br>fun [Euclidean2DPassage](-euclidean2-d-passage.html)(tail: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), head: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), passageShapeOnTail: [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>) |


## Functions


| Name | Summary |
|---|---|
| [crossingPointOnHead](crossing-point-on-head.html) | [jvm]<br>fun [crossingPointOnHead](crossing-point-on-head.html)(crossingPointOnTail: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)<br>Provided the [crossingPointOnTail](crossing-point-on-head.html) that an agent has reached (or will reach), this method computes the point belonging to the boundary of [head](head.html) that the agent should point towards to cross the passage (i.e. |
| [crossingPointOnTail](crossing-point-on-tail.html) | [jvm]<br>fun [crossingPointOnTail](crossing-point-on-tail.html)(position: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)<br>Provided the [position](crossing-point-on-tail.html) of an agent that may want to cross this passage, this method computes the point belonging to [passageShapeOnTail](passage-shape-on-tail.html) which is more convenient to cross. |
| [crossingPoints](crossing-points.html) | [jvm]<br>fun [crossingPoints](crossing-points.html)(position: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)): [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)><br>Provided the [position](crossing-points.html) of an agent that may want to cross this passage, this method returns a pair containing both [crossingPointOnTail](crossing-point-on-tail.html) and [crossingPointOnHead](crossing-point-on-head.html). |


## Properties


| Name | Summary |
|---|---|
| [head](head.html) | [jvm]<br>val [head](head.html): [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html) |
| [passageShapeOnTail](passage-shape-on-tail.html) | [jvm]<br>val [passageShapeOnTail](passage-shape-on-tail.html): [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)> |
| [tail](tail.html) | [jvm]<br>val [tail](tail.html): [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html) |


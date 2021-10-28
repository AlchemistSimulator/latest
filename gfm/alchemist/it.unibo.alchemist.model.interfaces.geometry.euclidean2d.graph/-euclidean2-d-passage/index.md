//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph](../index.md)/[Euclidean2DPassage](index.md)

# Euclidean2DPassage

[jvm]\
data class [Euclidean2DPassage](index.md)(**tail**: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), **head**: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), **passageShapeOnTail**: [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>)

Defines a passage between two [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md)s in an euclidean bidimensional space. The passage is oriented, which means it connects [tail](tail.md) to [head](head.md), but the opposite is not necessarily true. [tail](tail.md) and [head](head.md) can be non-adjacent (there can be some distance between them), this introduces navigation issues as agents may not know which direction to follow when crossing a passage. [passageShapeOnTail](passage-shape-on-tail.md) is a [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.md) representing the shape of the passage on [tail](tail.md)'s boundary (e.g. in indoor environments, the segment should represent the shape of the door between two rooms). [passageShapeOnTail](passage-shape-on-tail.md) must be determined so as to guarantee that [head](head.md) is reachable by throwing a ray from any point of the segment in its normal direction. This solves navigation issues as it provides agents with a direction to follow when crossing [Euclidean2DPassage](index.md)s (namely, the normal direction to [passageShapeOnTail](passage-shape-on-tail.md)).

## Constructors

| | |
|---|---|
| [Euclidean2DPassage](-euclidean2-d-passage.md) | [jvm]<br>fun [Euclidean2DPassage](-euclidean2-d-passage.md)(tail: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), head: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), passageShapeOnTail: [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>) |

## Functions

| Name | Summary |
|---|---|
| [crossingPointOnHead](crossing-point-on-head.md) | [jvm]<br>fun [crossingPointOnHead](crossing-point-on-head.md)(crossingPointOnTail: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)<br>Provided the [crossingPointOnTail](crossing-point-on-head.md) that an agent has reached (or will reach), this method computes the point belonging to the boundary of [head](head.md) that the agent should point towards to cross the passage (i.e. |
| [crossingPointOnTail](crossing-point-on-tail.md) | [jvm]<br>fun [crossingPointOnTail](crossing-point-on-tail.md)(position: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)<br>Provided the [position](crossing-point-on-tail.md) of an agent that may want to cross this passage, this method computes the point belonging to [passageShapeOnTail](passage-shape-on-tail.md) which is more convenient to cross. |
| [crossingPoints](crossing-points.md) | [jvm]<br>fun [crossingPoints](crossing-points.md)(position: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)): [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)><br>Provided the [position](crossing-points.md) of an agent that may want to cross this passage, this method returns a pair containing both [crossingPointOnTail](crossing-point-on-tail.md) and [crossingPointOnHead](crossing-point-on-head.md). |

## Properties

| Name | Summary |
|---|---|
| [head](head.md) | [jvm]<br>val [head](head.md): [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md) |
| [passageShapeOnTail](passage-shape-on-tail.md) | [jvm]<br>val [passageShapeOnTail](passage-shape-on-tail.md): [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)> |
| [tail](tail.md) | [jvm]<br>val [tail](tail.md): [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md) |

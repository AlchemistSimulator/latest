//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d](../index.md)/[Segment2D](index.md)

# Segment2D

[jvm]\
interface [Segment2D](index.md)<[P](index.md) : [Vector2D](../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.md)<[P](index.md)>>

Defines a line segment in a cartesian plane, endpoints are included.

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [jvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [closestPointTo](closest-point-to.md) | [jvm]<br>open fun [closestPointTo](closest-point-to.md)(point: [P](index.md)): [P](index.md)<br>Finds the point of the segment which is closest to the provided [point](closest-point-to.md). |
| [contains](contains.md) | [jvm]<br>open fun [contains](contains.md)(point: [P](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the segment contains a [point](contains.md). |
| [copyWith](copy-with.md) | [jvm]<br>abstract fun [copyWith](copy-with.md)(first: [P](index.md) = this.first, second: [P](index.md) = this.second): [Segment2D](index.md)<[P](index.md)><br>Creates a copy of this Segment2D using the specified [first](copy-with.md) and [second](copy-with.md) points. |
| [distanceTo](distance-to.md) | [jvm]<br>open fun [distanceTo](distance-to.md)(point: [P](index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the shortest distance between the segment and the given [point](distance-to.md).<br>[jvm]<br>open fun [distanceTo](distance-to.md)(other: [Segment2D](index.md)<[P](index.md)>): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the shortest distance between two segments (= the shortest distance between any two of their points). |
| [intersect](intersect.md) | [jvm]<br>open fun [intersect](intersect.md)(other: [Segment2D](index.md)<[P](index.md)>): [Intersection2D](../-intersection2-d/index.md)<[P](index.md)><br>Intersects two segments. |
| [intersectCircle](intersect-circle.md) | [jvm]<br>open fun [intersectCircle](intersect-circle.md)(center: [P](index.md), radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Intersection2D](../-intersection2-d/index.md)<[P](index.md)><br>Intersects a segment and a circle. |
| [isCollinearWith](is-collinear-with.md) | [jvm]<br>open fun [isCollinearWith](is-collinear-with.md)(point: [P](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if [first](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/index.html), [second](second.md) and [point](is-collinear-with.md) lie on a single line.<br>[jvm]<br>open fun [isCollinearWith](is-collinear-with.md)(other: [Segment2D](index.md)<[P](index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if two segments lie on a single line. |
| [isInRectangle](is-in-rectangle.md) | [jvm]<br>open fun [isInRectangle](is-in-rectangle.md)(origin: [Vector2D](../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.md)<*>, width: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), height: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if this segment is inside a rectangular region described by an [origin](is-in-rectangle.md), [width](is-in-rectangle.md) and [height](is-in-rectangle.md) (must be positive). |
| [isParallelTo](is-parallel-to.md) | [jvm]<br>open fun [isParallelTo](is-parallel-to.md)(other: [Segment2D](index.md)<[P](index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if two segments are parallel. |
| [overlapsWith](overlaps-with.md) | [jvm]<br>open fun [overlapsWith](overlaps-with.md)(other: [Segment2D](index.md)<[P](index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if two segments overlap (= are collinear and share one or more points). |
| [shrunk](shrunk.md) | [jvm]<br>open fun [shrunk](shrunk.md)(factor: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Segment2D](index.md)<[P](index.md)> |
| [toLine](to-line.md) | [jvm]<br>open fun [toLine](to-line.md)(): [Line2D](../-line2-d/index.md)<[P](index.md)> |
| [toRange](to-range.md) | [jvm]<br>open fun [toRange](to-range.md)(getXCoords: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = this.isHorizontal): [ClosedRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)><br>Maps the segment a [ClosedRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html), this is done by extracting either the X coordinates or the Y coordinates of the two endpoints of the segment. |

## Properties

| Name | Summary |
|---|---|
| [first](first.md) | [jvm]<br>abstract val [first](first.md): [P](index.md)<br>The first endpoint of the segment. |
| [isDegenerate](is-degenerate.md) | [jvm]<br>open val [isDegenerate](is-degenerate.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Indicates if the two endpoints coincide (= segment has zero length). |
| [isHorizontal](is-horizontal.md) | [jvm]<br>open val [isHorizontal](is-horizontal.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Indicates if the segment is aligned to the x-axis, this is true if [isDegenerate](is-degenerate.md). |
| [isVertical](is-vertical.md) | [jvm]<br>open val [isVertical](is-vertical.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Indicates if the segment is aligned to the y-axis, this is true if [isDegenerate](is-degenerate.md). |
| [length](length.md) | [jvm]<br>open val [length](length.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The length of the segment. |
| [midPoint](mid-point.md) | [jvm]<br>open val [midPoint](mid-point.md): [P](index.md)<br>The medium point of the segment. |
| [second](second.md) | [jvm]<br>abstract val [second](second.md): [P](index.md)<br>The second endpoint of the segment. |
| [toVector](to-vector.md) | [jvm]<br>open val [toVector](to-vector.md): [P](index.md)<br>The vector representing the movement from [first](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/index.html) to [second](second.md). |

## Inheritors

| Name |
|---|
| [Segment2DImpl](../../it.unibo.alchemist.model.implementations.geometry.euclidean2d/-segment2-d-impl/index.md) |

---
title: Segment2D
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d](../index.html)/[Segment2D](index.html)



# Segment2D



[jvm]\
interface [Segment2D](index.html)<[P](index.html) : [Vector2D](../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.html)<[P](index.html)>>

Defines a line segment in a cartesian plane, endpoints are included.



## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [closestPointTo](closest-point-to.html) | [jvm]<br>open fun [closestPointTo](closest-point-to.html)(point: [P](index.html)): [P](index.html)<br>Finds the point of the segment which is closest to the provided [point](closest-point-to.html). |
| [contains](contains.html) | [jvm]<br>open fun [contains](contains.html)(point: [P](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the segment contains a [point](contains.html). |
| [copyWith](copy-with.html) | [jvm]<br>abstract fun [copyWith](copy-with.html)(first: [P](index.html) = this.first, second: [P](index.html) = this.second): [Segment2D](index.html)<[P](index.html)><br>Creates a copy of this Segment2D using the specified [first](copy-with.html) and [second](copy-with.html) points. |
| [distanceTo](distance-to.html) | [jvm]<br>open fun [distanceTo](distance-to.html)(point: [P](index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the shortest distance between the segment and the given [point](distance-to.html).<br>[jvm]<br>open fun [distanceTo](distance-to.html)(other: [Segment2D](index.html)<[P](index.html)>): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the shortest distance between two segments (= the shortest distance between any two of their points). |
| [intersect](intersect.html) | [jvm]<br>open fun [intersect](intersect.html)(other: [Segment2D](index.html)<[P](index.html)>): [Intersection2D](../-intersection2-d/index.html)<[P](index.html)><br>Intersects two segments. |
| [intersectCircle](intersect-circle.html) | [jvm]<br>open fun [intersectCircle](intersect-circle.html)(center: [P](index.html), radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Intersection2D](../-intersection2-d/index.html)<[P](index.html)><br>Intersects a segment and a circle. |
| [isCollinearWith](is-collinear-with.html) | [jvm]<br>open fun [isCollinearWith](is-collinear-with.html)(point: [P](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if [first](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/index.html), [second](second.html) and [point](is-collinear-with.html) lie on a single line.<br>[jvm]<br>open fun [isCollinearWith](is-collinear-with.html)(other: [Segment2D](index.html)<[P](index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if two segments lie on a single line. |
| [isInRectangle](is-in-rectangle.html) | [jvm]<br>open fun [isInRectangle](is-in-rectangle.html)(origin: [Vector2D](../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.html)<*>, width: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), height: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if this segment is inside a rectangular region described by an [origin](is-in-rectangle.html), [width](is-in-rectangle.html) and [height](is-in-rectangle.html) (must be positive). |
| [isParallelTo](is-parallel-to.html) | [jvm]<br>open fun [isParallelTo](is-parallel-to.html)(other: [Segment2D](index.html)<[P](index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if two segments are parallel. |
| [overlapsWith](overlaps-with.html) | [jvm]<br>open fun [overlapsWith](overlaps-with.html)(other: [Segment2D](index.html)<[P](index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if two segments overlap (= are collinear and share one or more points). |
| [shrunk](shrunk.html) | [jvm]<br>open fun [shrunk](shrunk.html)(factor: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Segment2D](index.html)<[P](index.html)> |
| [toLine](to-line.html) | [jvm]<br>open fun [toLine](to-line.html)(): [Line2D](../-line2-d/index.html)<[P](index.html)> |
| [toRange](to-range.html) | [jvm]<br>open fun [toRange](to-range.html)(getXCoords: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = this.isHorizontal): [ClosedRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)><br>Maps the segment a [ClosedRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html), this is done by extracting either the X coordinates or the Y coordinates of the two endpoints of the segment. |


## Properties


| Name | Summary |
|---|---|
| [first](first.html) | [jvm]<br>abstract val [first](first.html): [P](index.html)<br>The first endpoint of the segment. |
| [isDegenerate](is-degenerate.html) | [jvm]<br>open val [isDegenerate](is-degenerate.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Indicates if the two endpoints coincide (= segment has zero length). |
| [isHorizontal](is-horizontal.html) | [jvm]<br>open val [isHorizontal](is-horizontal.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Indicates if the segment is aligned to the x-axis, this is true if [isDegenerate](is-degenerate.html). |
| [isVertical](is-vertical.html) | [jvm]<br>open val [isVertical](is-vertical.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Indicates if the segment is aligned to the y-axis, this is true if [isDegenerate](is-degenerate.html). |
| [length](length.html) | [jvm]<br>open val [length](length.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The length of the segment. |
| [midPoint](mid-point.html) | [jvm]<br>open val [midPoint](mid-point.html): [P](index.html)<br>The medium point of the segment. |
| [second](second.html) | [jvm]<br>abstract val [second](second.html): [P](index.html)<br>The second endpoint of the segment. |
| [toVector](to-vector.html) | [jvm]<br>open val [toVector](to-vector.html): [P](index.html)<br>The vector representing the movement from [first](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/index.html) to [second](second.html). |


## Inheritors


| Name |
|---|
| [Segment2DImpl](../../it.unibo.alchemist.model.implementations.geometry.euclidean2d/-segment2-d-impl/index.html) |


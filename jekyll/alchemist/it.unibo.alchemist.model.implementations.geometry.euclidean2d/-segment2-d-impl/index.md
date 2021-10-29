---
title: Segment2DImpl
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.geometry.euclidean2d](../index.html)/[Segment2DImpl](index.html)



# Segment2DImpl



[jvm]\
data class [Segment2DImpl](index.html)<[P](index.html) : [Vector2D](../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.html)<[P](index.html)>>(**first**: [P](index.html), **second**: [P](index.html)) : [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.html)<[P](index.html)> 

Implementation of a [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.html).



## Constructors


| | |
|---|---|
| [Segment2DImpl](-segment2-d-impl.html) | [jvm]<br>fun <[P](index.html) : [Vector2D](../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.html)<[P](index.html)>> [Segment2DImpl](-segment2-d-impl.html)(first: [P](index.html), second: [P](index.html)) |


## Functions


| Name | Summary |
|---|---|
| [closestPointTo](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/closest-point-to.html) | [jvm]<br>open fun [closestPointTo](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/closest-point-to.html)(point: [P](index.html)): [P](index.html)<br>Finds the point of the segment which is closest to the provided [point](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/closest-point-to.html). |
| [contains](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/contains.html) | [jvm]<br>open fun [contains](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/contains.html)(point: [P](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the segment contains a [point](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/contains.html). |
| [copyWith](copy-with.html) | [jvm]<br>open override fun [copyWith](copy-with.html)(first: [P](index.html), second: [P](index.html)): [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.html)<[P](index.html)><br>Creates a copy of this Segment2D using the specified [first](copy-with.html) and [second](copy-with.html) points. |
| [distanceTo](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/distance-to.html) | [jvm]<br>open fun [distanceTo](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/distance-to.html)(point: [P](index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the shortest distance between the segment and the given [point](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/distance-to.html).<br>[jvm]<br>open fun [distanceTo](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/distance-to.html)(other: [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.html)<[P](index.html)>): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the shortest distance between two segments (= the shortest distance between any two of their points). |
| [intersect](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/intersect.html) | [jvm]<br>open fun [intersect](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/intersect.html)(other: [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.html)<[P](index.html)>): [Intersection2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-intersection2-d/index.html)<[P](index.html)><br>Intersects two segments. |
| [intersectCircle](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/intersect-circle.html) | [jvm]<br>open fun [intersectCircle](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/intersect-circle.html)(center: [P](index.html), radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Intersection2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-intersection2-d/index.html)<[P](index.html)><br>Intersects a segment and a circle. |
| [isCollinearWith](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/is-collinear-with.html) | [jvm]<br>open fun [isCollinearWith](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/is-collinear-with.html)(point: [P](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if [first](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/index.html), [second](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/second.html) and [point](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/is-collinear-with.html) lie on a single line.<br>[jvm]<br>open fun [isCollinearWith](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/is-collinear-with.html)(other: [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.html)<[P](index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if two segments lie on a single line. |
| [isInRectangle](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/is-in-rectangle.html) | [jvm]<br>open fun [isInRectangle](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/is-in-rectangle.html)(origin: [Vector2D](../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.html)<*>, width: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), height: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if this segment is inside a rectangular region described by an [origin](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/is-in-rectangle.html), [width](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/is-in-rectangle.html) and [height](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/is-in-rectangle.html) (must be positive). |
| [isParallelTo](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/is-parallel-to.html) | [jvm]<br>open fun [isParallelTo](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/is-parallel-to.html)(other: [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.html)<[P](index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if two segments are parallel. |
| [overlapsWith](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/overlaps-with.html) | [jvm]<br>open fun [overlapsWith](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/overlaps-with.html)(other: [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.html)<[P](index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if two segments overlap (= are collinear and share one or more points). |
| [shrunk](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/shrunk.html) | [jvm]<br>open fun [shrunk](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/shrunk.html)(factor: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.html)<[P](index.html)> |
| [toLine](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/to-line.html) | [jvm]<br>open fun [toLine](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/to-line.html)(): [Line2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-line2-d/index.html)<[P](index.html)> |
| [toRange](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/to-range.html) | [jvm]<br>open fun [toRange](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/to-range.html)(getXCoords: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = this.isHorizontal): [ClosedRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)><br>Maps the segment a [ClosedRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html), this is done by extracting either the X coordinates or the Y coordinates of the two endpoints of the segment. |


## Properties


| Name | Summary |
|---|---|
| [first](first.html) | [jvm]<br>open override val [first](first.html): [P](index.html)<br>The first endpoint of the segment. |
| [isDegenerate](index.html#-1448140262%2FProperties%2F-134779887) | [jvm]<br>open val [isDegenerate](index.html#-1448140262%2FProperties%2F-134779887): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Indicates if the two endpoints coincide (= segment has zero length). |
| [isHorizontal](index.html#959379116%2FProperties%2F-134779887) | [jvm]<br>open val [isHorizontal](index.html#959379116%2FProperties%2F-134779887): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Indicates if the segment is aligned to the x-axis, this is true if [isDegenerate](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/is-degenerate.html). |
| [isVertical](index.html#1540465754%2FProperties%2F-134779887) | [jvm]<br>open val [isVertical](index.html#1540465754%2FProperties%2F-134779887): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Indicates if the segment is aligned to the y-axis, this is true if [isDegenerate](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/is-degenerate.html). |
| [length](index.html#1068991860%2FProperties%2F-134779887) | [jvm]<br>open val [length](index.html#1068991860%2FProperties%2F-134779887): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The length of the segment. |
| [midPoint](index.html#-1630281934%2FProperties%2F-134779887) | [jvm]<br>open val [midPoint](index.html#-1630281934%2FProperties%2F-134779887): [P](index.html)<br>The medium point of the segment. |
| [second](second.html) | [jvm]<br>open override val [second](second.html): [P](index.html)<br>The second endpoint of the segment. |
| [toVector](index.html#-920278916%2FProperties%2F-134779887) | [jvm]<br>open val [toVector](index.html#-920278916%2FProperties%2F-134779887): [P](index.html)<br>The vector representing the movement from [first](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/index.html) to [second](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/second.html). |


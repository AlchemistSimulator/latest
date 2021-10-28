//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d](../index.md)/[Line2D](index.md)

# Line2D

[jvm]\
interface [Line2D](index.md)<[P](index.md) : [Vector2D](../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.md)<[P](index.md)>>

Defines a straight line in a cartesian plane.

## Functions

| Name | Summary |
|---|---|
| [contains](contains.md) | [jvm]<br>abstract fun [contains](contains.md)(point: [P](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the [point](contains.md) belongs to this line. |
| [findPoint](find-point.md) | [jvm]<br>abstract fun [findPoint](find-point.md)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](index.md)<br>Finds the point belonging to the line with the given [x](find-point.md)-coordinate. |
| [intersect](intersect.md) | [jvm]<br>abstract fun [intersect](intersect.md)(other: [Line2D](index.md)<[P](index.md)>): [Intersection2D](../-intersection2-d/index.md)<[P](index.md)><br>Intersects two lines. |
| [intersectCircle](intersect-circle.md) | [jvm]<br>abstract fun [intersectCircle](intersect-circle.md)(center: [P](index.md), radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Intersection2D](../-intersection2-d/index.md)<[P](index.md)><br>Intersects a line and a circle. |
| [isParallelTo](is-parallel-to.md) | [jvm]<br>abstract fun [isParallelTo](is-parallel-to.md)(other: [Line2D](index.md)<[P](index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if two lines are parallel. |

## Properties

| Name | Summary |
|---|---|
| [isHorizontal](is-horizontal.md) | [jvm]<br>abstract val [isHorizontal](is-horizontal.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Indicates if the line is aligned to the x-axis. |
| [isVertical](is-vertical.md) | [jvm]<br>abstract val [isVertical](is-vertical.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Indicates if the line is aligned to the y-axis. |
| [slope](slope.md) | [jvm]<br>abstract val [slope](slope.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The slope of the line, if [isVertical](is-vertical.md) this is undefined (= [Double.NaN](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/-na-n.html)). |
| [xIntercept](x-intercept.md) | [jvm]<br>abstract val [xIntercept](x-intercept.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The x-coordinate of the x-intercept (= the point where the line intersects the x-axis). |
| [yIntercept](y-intercept.md) | [jvm]<br>abstract val [yIntercept](y-intercept.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The y-coordinate of the y-intercept (= the point where the line intersects the y-axis). |

## Inheritors

| Name |
|---|
| [SlopeInterceptLine2D](../../it.unibo.alchemist.model.implementations.geometry.euclidean2d/-slope-intercept-line2-d/index.md) |

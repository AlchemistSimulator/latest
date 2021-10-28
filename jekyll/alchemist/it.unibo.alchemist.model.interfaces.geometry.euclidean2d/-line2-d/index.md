---
title: Line2D
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d](../index.html)/[Line2D](index.html)



# Line2D



[jvm]\
interface [Line2D](index.html)<[P](index.html) : [Vector2D](../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.html)<[P](index.html)>>

Defines a straight line in a cartesian plane.



## Functions


| Name | Summary |
|---|---|
| [contains](contains.html) | [jvm]<br>abstract fun [contains](contains.html)(point: [P](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the [point](contains.html) belongs to this line. |
| [findPoint](find-point.html) | [jvm]<br>abstract fun [findPoint](find-point.html)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](index.html)<br>Finds the point belonging to the line with the given [x](find-point.html)-coordinate. |
| [intersect](intersect.html) | [jvm]<br>abstract fun [intersect](intersect.html)(other: [Line2D](index.html)<[P](index.html)>): [Intersection2D](../-intersection2-d/index.html)<[P](index.html)><br>Intersects two lines. |
| [intersectCircle](intersect-circle.html) | [jvm]<br>abstract fun [intersectCircle](intersect-circle.html)(center: [P](index.html), radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Intersection2D](../-intersection2-d/index.html)<[P](index.html)><br>Intersects a line and a circle. |
| [isParallelTo](is-parallel-to.html) | [jvm]<br>abstract fun [isParallelTo](is-parallel-to.html)(other: [Line2D](index.html)<[P](index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if two lines are parallel. |


## Properties


| Name | Summary |
|---|---|
| [isHorizontal](is-horizontal.html) | [jvm]<br>abstract val [isHorizontal](is-horizontal.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Indicates if the line is aligned to the x-axis. |
| [isVertical](is-vertical.html) | [jvm]<br>abstract val [isVertical](is-vertical.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Indicates if the line is aligned to the y-axis. |
| [slope](slope.html) | [jvm]<br>abstract val [slope](slope.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The slope of the line, if [isVertical](is-vertical.html) this is undefined (= [Double.NaN](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/-na-n.html)). |
| [xIntercept](x-intercept.html) | [jvm]<br>abstract val [xIntercept](x-intercept.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The x-coordinate of the x-intercept (= the point where the line intersects the x-axis). |
| [yIntercept](y-intercept.html) | [jvm]<br>abstract val [yIntercept](y-intercept.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The y-coordinate of the y-intercept (= the point where the line intersects the y-axis). |


## Inheritors


| Name |
|---|
| [SlopeInterceptLine2D](../../it.unibo.alchemist.model.implementations.geometry.euclidean2d/-slope-intercept-line2-d/index.html) |


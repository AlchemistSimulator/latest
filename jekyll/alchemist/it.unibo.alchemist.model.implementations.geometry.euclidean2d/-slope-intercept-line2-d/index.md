---
title: SlopeInterceptLine2D
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.geometry.euclidean2d](../index.html)/[SlopeInterceptLine2D](index.html)



# SlopeInterceptLine2D



[jvm]\
class [SlopeInterceptLine2D](index.html)<[P](index.html) : [Vector2D](../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.html)<[P](index.html)>> : [Line2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-line2-d/index.html)<[P](index.html)> 

A [Line2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-line2-d/index.html) represented in the slope-intercept form: y = [slope](slope.html) * x + [yIntercept](y-intercept.html). Doubles are only compared with MathUtils.fuzzyEquals.



## Constructors


| | |
|---|---|
| [SlopeInterceptLine2D](-slope-intercept-line2-d.html) | [jvm]<br>fun <[P](index.html) : [Vector2D](../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.html)<[P](index.html)>> [SlopeInterceptLine2D](-slope-intercept-line2-d.html)(slope: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), yIntercept: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), createPoint: ([Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) -> [P](index.html))<br>Creates a non-vertical line given its slope and yIntercept. |
| [SlopeInterceptLine2D](-slope-intercept-line2-d.html) | [jvm]<br>fun <[P](index.html) : [Vector2D](../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.html)<[P](index.html)>> [SlopeInterceptLine2D](-slope-intercept-line2-d.html)(xIntercept: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), createPoint: ([Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) -> [P](index.html))<br>Creates a vertical line given its xIntercept. |


## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [coincidesWith](coincides-with.html) | [jvm]<br>fun [coincidesWith](coincides-with.html)(other: [Line2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-line2-d/index.html)<*>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if two lines coincide. |
| [contains](contains.html) | [jvm]<br>open override fun [contains](contains.html)(point: [P](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the [point](contains.html) belongs to this line. |
| [equals](equals.html) | [jvm]<br>open operator override fun [equals](equals.html)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if [other](equals.html) is a [Line2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-line2-d/index.html) and if it [coincidesWith](coincides-with.html) this one. |
| [findPoint](find-point.html) | [jvm]<br>open override fun [findPoint](find-point.html)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](index.html)<br>Finds the point belonging to the line with the given [x](find-point.html)-coordinate. |
| [findY](find-y.html) | [jvm]<br>fun [findY](find-y.html)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Solves the line equation for the given [x](find-y.html). |
| [hashCode](hash-code.html) | [jvm]<br>open override fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Uses [slope](slope.html), [yIntercept](y-intercept.html) and [xIntercept](x-intercept.html). |
| [intersect](intersect.html) | [jvm]<br>open override fun [intersect](intersect.html)(other: [Line2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-line2-d/index.html)<[P](index.html)>): [Intersection2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-intersection2-d/index.html)<[P](index.html)><br>Intersects two lines. |
| [intersectCircle](intersect-circle.html) | [jvm]<br>open override fun [intersectCircle](intersect-circle.html)(center: [P](index.html), radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Intersection2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-intersection2-d/index.html)<[P](index.html)><br>Intersects a line and a circle. |
| [isParallelTo](is-parallel-to.html) | [jvm]<br>open override fun [isParallelTo](is-parallel-to.html)(other: [Line2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-line2-d/index.html)<[P](index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if two lines are parallel. |


## Properties


| Name | Summary |
|---|---|
| [isHorizontal](is-horizontal.html) | [jvm]<br>open override val [isHorizontal](is-horizontal.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Indicates if the line is aligned to the x-axis. |
| [isVertical](is-vertical.html) | [jvm]<br>open override val [isVertical](is-vertical.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Indicates if the line is aligned to the y-axis. |
| [slope](slope.html) | [jvm]<br>open override val [slope](slope.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The slope of the line, if [isVertical](is-vertical.html) this is undefined (= [Double.NaN](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/-na-n.html)). |
| [xIntercept](x-intercept.html) | [jvm]<br>open override val [xIntercept](x-intercept.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The x-coordinate of the x-intercept (= the point where the line intersects the x-axis). |
| [yIntercept](y-intercept.html) | [jvm]<br>open override val [yIntercept](y-intercept.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The y-coordinate of the y-intercept (= the point where the line intersects the y-axis). |


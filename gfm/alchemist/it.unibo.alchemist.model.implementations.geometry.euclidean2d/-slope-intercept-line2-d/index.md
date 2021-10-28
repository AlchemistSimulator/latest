//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.geometry.euclidean2d](../index.md)/[SlopeInterceptLine2D](index.md)

# SlopeInterceptLine2D

[jvm]\
class [SlopeInterceptLine2D](index.md)<[P](index.md) : [Vector2D](../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.md)<[P](index.md)>> : [Line2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-line2-d/index.md)<[P](index.md)> 

A [Line2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-line2-d/index.md) represented in the slope-intercept form: y = [slope](slope.md) * x + [yIntercept](y-intercept.md). Doubles are only compared with MathUtils.fuzzyEquals.

## Constructors

| | |
|---|---|
| [SlopeInterceptLine2D](-slope-intercept-line2-d.md) | [jvm]<br>fun <[P](index.md) : [Vector2D](../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.md)<[P](index.md)>> [SlopeInterceptLine2D](-slope-intercept-line2-d.md)(slope: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), yIntercept: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), createPoint: ([Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) -> [P](index.md))<br>Creates a non-vertical line given its slope and yIntercept. |
| [SlopeInterceptLine2D](-slope-intercept-line2-d.md) | [jvm]<br>fun <[P](index.md) : [Vector2D](../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.md)<[P](index.md)>> [SlopeInterceptLine2D](-slope-intercept-line2-d.md)(xIntercept: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), createPoint: ([Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) -> [P](index.md))<br>Creates a vertical line given its xIntercept. |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [jvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [coincidesWith](coincides-with.md) | [jvm]<br>fun [coincidesWith](coincides-with.md)(other: [Line2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-line2-d/index.md)<*>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if two lines coincide. |
| [contains](contains.md) | [jvm]<br>open override fun [contains](contains.md)(point: [P](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the [point](contains.md) belongs to this line. |
| [equals](equals.md) | [jvm]<br>open operator override fun [equals](equals.md)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if [other](equals.md) is a [Line2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-line2-d/index.md) and if it [coincidesWith](coincides-with.md) this one. |
| [findPoint](find-point.md) | [jvm]<br>open override fun [findPoint](find-point.md)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](index.md)<br>Finds the point belonging to the line with the given [x](find-point.md)-coordinate. |
| [findY](find-y.md) | [jvm]<br>fun [findY](find-y.md)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Solves the line equation for the given [x](find-y.md). |
| [hashCode](hash-code.md) | [jvm]<br>open override fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Uses [slope](slope.md), [yIntercept](y-intercept.md) and [xIntercept](x-intercept.md). |
| [intersect](intersect.md) | [jvm]<br>open override fun [intersect](intersect.md)(other: [Line2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-line2-d/index.md)<[P](index.md)>): [Intersection2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-intersection2-d/index.md)<[P](index.md)><br>Intersects two lines. |
| [intersectCircle](intersect-circle.md) | [jvm]<br>open override fun [intersectCircle](intersect-circle.md)(center: [P](index.md), radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Intersection2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-intersection2-d/index.md)<[P](index.md)><br>Intersects a line and a circle. |
| [isParallelTo](is-parallel-to.md) | [jvm]<br>open override fun [isParallelTo](is-parallel-to.md)(other: [Line2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-line2-d/index.md)<[P](index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if two lines are parallel. |

## Properties

| Name | Summary |
|---|---|
| [isHorizontal](is-horizontal.md) | [jvm]<br>open override val [isHorizontal](is-horizontal.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Indicates if the line is aligned to the x-axis. |
| [isVertical](is-vertical.md) | [jvm]<br>open override val [isVertical](is-vertical.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Indicates if the line is aligned to the y-axis. |
| [slope](slope.md) | [jvm]<br>open override val [slope](slope.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The slope of the line, if [isVertical](is-vertical.md) this is undefined (= [Double.NaN](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/-na-n.html)). |
| [xIntercept](x-intercept.md) | [jvm]<br>open override val [xIntercept](x-intercept.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The x-coordinate of the x-intercept (= the point where the line intersects the x-axis). |
| [yIntercept](y-intercept.md) | [jvm]<br>open override val [yIntercept](y-intercept.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The y-coordinate of the y-intercept (= the point where the line intersects the y-axis). |

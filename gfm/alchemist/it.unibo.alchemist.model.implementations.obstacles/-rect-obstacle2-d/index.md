//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.obstacles](../index.md)/[RectObstacle2D](index.md)

# RectObstacle2D

[jvm]\
class [RectObstacle2D](index.md)<[V](index.md) : [Vector2D](../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.md)<[V](../../it.unibo.alchemist.model.interfaces/-obstacle2-d/index.md)>?> : [Rectangle2D.Double](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Rectangle2D.Double.html), [Obstacle2D](../../it.unibo.alchemist.model.interfaces/-obstacle2-d/index.md)<[V](../../it.unibo.alchemist.model.interfaces/-obstacle2-d/index.md)> 

This class implements a rectangular obstacle, whose sides are parallel to the cartesian axis.

## Parameters

jvm

| | |
|---|---|
| <V> | [Vector2D](../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.md) type |

## Constructors

| | |
|---|---|
| [RectObstacle2D](-rect-obstacle2-d.md) | [jvm]<br>open fun [RectObstacle2D](-rect-obstacle2-d.md)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), w: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), h: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Builds a new RectObstacle2D, given a point, the width and the height. |

## Functions

| Name | Summary |
|---|---|
| [add](index.md#-947440994%2FFunctions%2F-267951372) | [jvm]<br>open fun [add](index.md#-947440994%2FFunctions%2F-267951372)(newx: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), newy: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [clone](index.md#1715677205%2FFunctions%2F-267951372) | [jvm]<br>open fun [clone](index.md#1715677205%2FFunctions%2F-267951372)(): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html) |
| [contains](contains.md) | [jvm]<br>open fun [contains](contains.md)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [createIntersection](index.md#-2079001415%2FFunctions%2F-267951372) | [jvm]<br>open fun [createIntersection](index.md#-2079001415%2FFunctions%2F-267951372)(r: [Rectangle2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Rectangle2D.html)): [Rectangle2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Rectangle2D.html) |
| [createUnion](index.md#1173285779%2FFunctions%2F-267951372) | [jvm]<br>open fun [createUnion](index.md#1173285779%2FFunctions%2F-267951372)(r: [Rectangle2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Rectangle2D.html)): [Rectangle2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Rectangle2D.html) |
| [equals](index.md#579106470%2FFunctions%2F-267951372) | [jvm]<br>open fun [equals](index.md#579106470%2FFunctions%2F-267951372)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getBounds](index.md#-1331745529%2FFunctions%2F-267951372) | [jvm]<br>open fun [getBounds](index.md#-1331745529%2FFunctions%2F-267951372)(): [Rectangle](https://docs.oracle.com/javase/8/docs/api/java/awt/Rectangle.html) |
| [getBounds2D](index.md#1436210010%2FFunctions%2F-267951372) | [jvm]<br>open fun [getBounds2D](index.md#1436210010%2FFunctions%2F-267951372)(): [Rectangle2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Rectangle2D.html) |
| [getCenterX](index.md#-260774917%2FFunctions%2F-267951372) | [jvm]<br>open fun [getCenterX](index.md#-260774917%2FFunctions%2F-267951372)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getCenterY](index.md#-229755110%2FFunctions%2F-267951372) | [jvm]<br>open fun [getCenterY](index.md#-229755110%2FFunctions%2F-267951372)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getFrame](index.md#-1009238863%2FFunctions%2F-267951372) | [jvm]<br>open fun [getFrame](index.md#-1009238863%2FFunctions%2F-267951372)(): [Rectangle2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Rectangle2D.html) |
| [getHeight](index.md#-546258182%2FFunctions%2F-267951372) | [jvm]<br>open fun [getHeight](index.md#-546258182%2FFunctions%2F-267951372)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getId](index.md#-1192365972%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getId](index.md#-1192365972%2FFunctions%2F-267951372)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMaxX](index.md#-178639640%2FFunctions%2F-267951372) | [jvm]<br>open fun [getMaxX](index.md#-178639640%2FFunctions%2F-267951372)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getMaxY](index.md#-147619833%2FFunctions%2F-267951372) | [jvm]<br>open fun [getMaxY](index.md#-147619833%2FFunctions%2F-267951372)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getMinX](index.md#1052229718%2FFunctions%2F-267951372) | [jvm]<br>open fun [getMinX](index.md#1052229718%2FFunctions%2F-267951372)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getMinY](index.md#1083249525%2FFunctions%2F-267951372) | [jvm]<br>open fun [getMinY](index.md#1083249525%2FFunctions%2F-267951372)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getPathIterator](index.md#1569558706%2FFunctions%2F-267951372) | [jvm]<br>open fun [getPathIterator](index.md#1569558706%2FFunctions%2F-267951372)(at: [AffineTransform](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/AffineTransform.html)): [PathIterator](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/PathIterator.html) |
| [getWidth](index.md#-1917675085%2FFunctions%2F-267951372) | [jvm]<br>open fun [getWidth](index.md#-1917675085%2FFunctions%2F-267951372)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getX](index.md#200847681%2FFunctions%2F-267951372) | [jvm]<br>open fun [getX](index.md#200847681%2FFunctions%2F-267951372)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getY](index.md#231867488%2FFunctions%2F-267951372) | [jvm]<br>open fun [getY](index.md#231867488%2FFunctions%2F-267951372)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [hashCode](index.md#1567294973%2FFunctions%2F-267951372) | [jvm]<br>open fun [hashCode](index.md#1567294973%2FFunctions%2F-267951372)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [intersect](index.md#-2628380%2FFunctions%2F-267951372) | [jvm]<br>open fun [intersect](index.md#-2628380%2FFunctions%2F-267951372)(src1: [Rectangle2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Rectangle2D.html), src2: [Rectangle2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Rectangle2D.html), dest: [Rectangle2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Rectangle2D.html)) |
| [intersects](index.md#-1657037413%2FFunctions%2F-267951372) | [jvm]<br>open fun [intersects](index.md#-1657037413%2FFunctions%2F-267951372)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), w: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), h: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [intersectsLine](index.md#330263343%2FFunctions%2F-267951372) | [jvm]<br>open fun [intersectsLine](index.md#330263343%2FFunctions%2F-267951372)(x1: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y1: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), x2: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y2: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isEmpty](index.md#723010068%2FFunctions%2F-267951372) | [jvm]<br>open fun [isEmpty](index.md#723010068%2FFunctions%2F-267951372)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [nearestIntersection](nearest-intersection.md) | [jvm]<br>open fun [nearestIntersection](nearest-intersection.md)(start: [V](../../it.unibo.alchemist.model.interfaces/-obstacle2-d/index.md), end: [V](../../it.unibo.alchemist.model.interfaces/-obstacle2-d/index.md)): [V](../../it.unibo.alchemist.model.interfaces/-obstacle2-d/index.md) |
| [next](next.md) | [jvm]<br>@NotNull()<br>open fun [next](next.md)(@NotNull()start: @NotNull()[V](index.md), @NotNull()end: @NotNull()[V](index.md)): @NotNull()[V](index.md) |
| [outcode](index.md#-382575421%2FFunctions%2F-267951372) | [jvm]<br>open fun [outcode](index.md#-382575421%2FFunctions%2F-267951372)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [setFrame](index.md#737722450%2FFunctions%2F-267951372) | [jvm]<br>open fun [setFrame](index.md#737722450%2FFunctions%2F-267951372)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), w: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), h: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [setFrameFromCenter](index.md#1702829761%2FFunctions%2F-267951372) | [jvm]<br>open fun [setFrameFromCenter](index.md#1702829761%2FFunctions%2F-267951372)(centerX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), centerY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), cornerX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), cornerY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [setFrameFromDiagonal](index.md#1331014689%2FFunctions%2F-267951372) | [jvm]<br>open fun [setFrameFromDiagonal](index.md#1331014689%2FFunctions%2F-267951372)(x1: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y1: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), x2: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y2: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [setRect](index.md#1477571438%2FFunctions%2F-267951372) | [jvm]<br>open fun [setRect](index.md#1477571438%2FFunctions%2F-267951372)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), w: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), h: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [union](index.md#-1849481196%2FFunctions%2F-267951372) | [jvm]<br>open fun [union](index.md#-1849481196%2FFunctions%2F-267951372)(src1: [Rectangle2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Rectangle2D.html), src2: [Rectangle2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Rectangle2D.html), dest: [Rectangle2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Rectangle2D.html)) |

## Properties

| Name | Summary |
|---|---|
| [id](id.md) | [jvm]<br>private val [id](id.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [maxX](max-x.md) | [jvm]<br>private val [maxX](max-x.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [maxY](max-y.md) | [jvm]<br>private val [maxY](max-y.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [minX](min-x.md) | [jvm]<br>private val [minX](min-x.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [minY](min-y.md) | [jvm]<br>private val [minY](min-y.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |

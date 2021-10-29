---
title: RectObstacle2D
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.obstacles](../index.html)/[RectObstacle2D](index.html)



# RectObstacle2D



[jvm]\
class [RectObstacle2D](index.html)<[V](index.html) : [Vector2D](../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.html)<[V](../../it.unibo.alchemist.model.interfaces/-obstacle2-d/index.html)>?> : [Rectangle2D.Double](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Rectangle2D.Double.html), [Obstacle2D](../../it.unibo.alchemist.model.interfaces/-obstacle2-d/index.html)<[V](../../it.unibo.alchemist.model.interfaces/-obstacle2-d/index.html)> 

This class implements a rectangular obstacle, whose sides are parallel to the cartesian axis.



## Parameters


jvm

| | |
|---|---|
| <V> | [Vector2D](../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.html) type |



## Constructors


| | |
|---|---|
| [RectObstacle2D](-rect-obstacle2-d.html) | [jvm]<br>open fun [RectObstacle2D](-rect-obstacle2-d.html)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), w: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), h: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Builds a new RectObstacle2D, given a point, the width and the height. |


## Functions


| Name | Summary |
|---|---|
| [add](index.html#-947440994%2FFunctions%2F-134779887) | [jvm]<br>open fun [add](index.html#-947440994%2FFunctions%2F-134779887)(newx: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), newy: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [clone](index.html#1715677205%2FFunctions%2F-134779887) | [jvm]<br>open fun [clone](index.html#1715677205%2FFunctions%2F-134779887)(): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html) |
| [contains](contains.html) | [jvm]<br>open fun [contains](contains.html)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [createIntersection](index.html#-2079001415%2FFunctions%2F-134779887) | [jvm]<br>open fun [createIntersection](index.html#-2079001415%2FFunctions%2F-134779887)(r: [Rectangle2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Rectangle2D.html)): [Rectangle2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Rectangle2D.html) |
| [createUnion](index.html#1173285779%2FFunctions%2F-134779887) | [jvm]<br>open fun [createUnion](index.html#1173285779%2FFunctions%2F-134779887)(r: [Rectangle2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Rectangle2D.html)): [Rectangle2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Rectangle2D.html) |
| [equals](index.html#579106470%2FFunctions%2F-134779887) | [jvm]<br>open fun [equals](index.html#579106470%2FFunctions%2F-134779887)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getBounds](index.html#-1331745529%2FFunctions%2F-134779887) | [jvm]<br>open fun [getBounds](index.html#-1331745529%2FFunctions%2F-134779887)(): [Rectangle](https://docs.oracle.com/javase/8/docs/api/java/awt/Rectangle.html) |
| [getBounds2D](index.html#1436210010%2FFunctions%2F-134779887) | [jvm]<br>open fun [getBounds2D](index.html#1436210010%2FFunctions%2F-134779887)(): [Rectangle2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Rectangle2D.html) |
| [getCenterX](index.html#-260774917%2FFunctions%2F-134779887) | [jvm]<br>open fun [getCenterX](index.html#-260774917%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getCenterY](index.html#-229755110%2FFunctions%2F-134779887) | [jvm]<br>open fun [getCenterY](index.html#-229755110%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getFrame](index.html#-1009238863%2FFunctions%2F-134779887) | [jvm]<br>open fun [getFrame](index.html#-1009238863%2FFunctions%2F-134779887)(): [Rectangle2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Rectangle2D.html) |
| [getHeight](index.html#-546258182%2FFunctions%2F-134779887) | [jvm]<br>open fun [getHeight](index.html#-546258182%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getId](index.html#-1192365972%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getId](index.html#-1192365972%2FFunctions%2F-134779887)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMaxX](index.html#-178639640%2FFunctions%2F-134779887) | [jvm]<br>open fun [getMaxX](index.html#-178639640%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getMaxY](index.html#-147619833%2FFunctions%2F-134779887) | [jvm]<br>open fun [getMaxY](index.html#-147619833%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getMinX](index.html#1052229718%2FFunctions%2F-134779887) | [jvm]<br>open fun [getMinX](index.html#1052229718%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getMinY](index.html#1083249525%2FFunctions%2F-134779887) | [jvm]<br>open fun [getMinY](index.html#1083249525%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getPathIterator](index.html#1569558706%2FFunctions%2F-134779887) | [jvm]<br>open fun [getPathIterator](index.html#1569558706%2FFunctions%2F-134779887)(at: [AffineTransform](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/AffineTransform.html)): [PathIterator](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/PathIterator.html) |
| [getWidth](index.html#-1917675085%2FFunctions%2F-134779887) | [jvm]<br>open fun [getWidth](index.html#-1917675085%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getX](index.html#200847681%2FFunctions%2F-134779887) | [jvm]<br>open fun [getX](index.html#200847681%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getY](index.html#231867488%2FFunctions%2F-134779887) | [jvm]<br>open fun [getY](index.html#231867488%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [hashCode](index.html#1567294973%2FFunctions%2F-134779887) | [jvm]<br>open fun [hashCode](index.html#1567294973%2FFunctions%2F-134779887)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [intersect](index.html#-2628380%2FFunctions%2F-134779887) | [jvm]<br>open fun [intersect](index.html#-2628380%2FFunctions%2F-134779887)(src1: [Rectangle2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Rectangle2D.html), src2: [Rectangle2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Rectangle2D.html), dest: [Rectangle2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Rectangle2D.html)) |
| [intersects](index.html#-1657037413%2FFunctions%2F-134779887) | [jvm]<br>open fun [intersects](index.html#-1657037413%2FFunctions%2F-134779887)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), w: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), h: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [intersectsLine](index.html#330263343%2FFunctions%2F-134779887) | [jvm]<br>open fun [intersectsLine](index.html#330263343%2FFunctions%2F-134779887)(x1: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y1: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), x2: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y2: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isEmpty](index.html#723010068%2FFunctions%2F-134779887) | [jvm]<br>open fun [isEmpty](index.html#723010068%2FFunctions%2F-134779887)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [nearestIntersection](nearest-intersection.html) | [jvm]<br>open fun [nearestIntersection](nearest-intersection.html)(start: [V](../../it.unibo.alchemist.model.interfaces/-obstacle2-d/index.html), end: [V](../../it.unibo.alchemist.model.interfaces/-obstacle2-d/index.html)): [V](../../it.unibo.alchemist.model.interfaces/-obstacle2-d/index.html) |
| [next](next.html) | [jvm]<br>@NotNull()<br>open fun [next](next.html)(@NotNull()start: @NotNull()[V](index.html), @NotNull()end: @NotNull()[V](index.html)): @NotNull()[V](index.html) |
| [outcode](index.html#-382575421%2FFunctions%2F-134779887) | [jvm]<br>open fun [outcode](index.html#-382575421%2FFunctions%2F-134779887)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [setFrame](index.html#737722450%2FFunctions%2F-134779887) | [jvm]<br>open fun [setFrame](index.html#737722450%2FFunctions%2F-134779887)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), w: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), h: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [setFrameFromCenter](index.html#1702829761%2FFunctions%2F-134779887) | [jvm]<br>open fun [setFrameFromCenter](index.html#1702829761%2FFunctions%2F-134779887)(centerX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), centerY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), cornerX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), cornerY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [setFrameFromDiagonal](index.html#1331014689%2FFunctions%2F-134779887) | [jvm]<br>open fun [setFrameFromDiagonal](index.html#1331014689%2FFunctions%2F-134779887)(x1: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y1: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), x2: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y2: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [setRect](index.html#1477571438%2FFunctions%2F-134779887) | [jvm]<br>open fun [setRect](index.html#1477571438%2FFunctions%2F-134779887)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), w: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), h: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [union](index.html#-1849481196%2FFunctions%2F-134779887) | [jvm]<br>open fun [union](index.html#-1849481196%2FFunctions%2F-134779887)(src1: [Rectangle2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Rectangle2D.html), src2: [Rectangle2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Rectangle2D.html), dest: [Rectangle2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Rectangle2D.html)) |


## Properties


| Name | Summary |
|---|---|
| [id](id.html) | [jvm]<br>private val [id](id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [maxX](max-x.html) | [jvm]<br>private val [maxX](max-x.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [maxY](max-y.html) | [jvm]<br>private val [maxY](max-y.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [minX](min-x.html) | [jvm]<br>private val [minX](min-x.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [minY](min-y.html) | [jvm]<br>private val [minY](min-y.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |


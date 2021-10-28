//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Obstacle2D](index.md)

# Obstacle2D

[jvm]\
interface [Obstacle2D](index.md)<[V](index.md) : [Vector2D](../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.md)<[V](index.md)>?> : [Obstacle](../-obstacle/index.md)<[V](index.md)> , [Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html)

An [Obstacle](../-obstacle/index.md) in a bidimensional space.

## Parameters

jvm

| | |
|---|---|
| <V> | the vector type for the space in which this obstacle is placed. |

## Functions

| Name | Summary |
|---|---|
| [contains](index.md#822681516%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [contains](index.md#822681516%2FFunctions%2F-267951372)(p: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), p1: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getBounds](index.md#975947261%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getBounds](index.md#975947261%2FFunctions%2F-267951372)(): [Rectangle](https://docs.oracle.com/javase/8/docs/api/java/awt/Rectangle.html) |
| [getBounds2D](index.md#624660459%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getBounds2D](index.md#624660459%2FFunctions%2F-267951372)(): [Rectangle2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Rectangle2D.html) |
| [getId](../../it.unibo.alchemist.model.implementations.obstacles/-rect-obstacle2-d/index.md#-1192365972%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getId](../../it.unibo.alchemist.model.implementations.obstacles/-rect-obstacle2-d/index.md#-1192365972%2FFunctions%2F-267951372)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getPathIterator](index.md#-997667124%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getPathIterator](index.md#-997667124%2FFunctions%2F-267951372)(p: [AffineTransform](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/AffineTransform.html)): [PathIterator](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/PathIterator.html) |
| [intersects](index.md#297445569%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [intersects](index.md#297445569%2FFunctions%2F-267951372)(p: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), p1: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), p2: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), p3: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [nearestIntersection](index.md#-1089506749%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [nearestIntersection](index.md#-1089506749%2FFunctions%2F-267951372)(p: [V](index.md), p1: [V](index.md)): [V](index.md) |
| [next](index.md#-1797662097%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [next](index.md#-1797662097%2FFunctions%2F-267951372)(p: [V](index.md), p1: [V](index.md)): [V](index.md) |

## Inheritors

| Name |
|---|
| [RectObstacle2D](../../it.unibo.alchemist.model.implementations.obstacles/-rect-obstacle2-d/index.md) |

---
title: Obstacle2D
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Obstacle2D](index.html)



# Obstacle2D



[jvm]\
interface [Obstacle2D](index.html)<[V](index.html) : [Vector2D](../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.html)<[V](index.html)>?> : [Obstacle](../-obstacle/index.html)<[V](index.html)> , [Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html)

An [Obstacle](../-obstacle/index.html) in a bidimensional space.



## Parameters


jvm

| | |
|---|---|
| <V> | the vector type for the space in which this obstacle is placed. |



## Functions


| Name | Summary |
|---|---|
| [contains](index.html#822681516%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [contains](index.html#822681516%2FFunctions%2F-134779887)(p: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), p1: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getBounds](index.html#975947261%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getBounds](index.html#975947261%2FFunctions%2F-134779887)(): [Rectangle](https://docs.oracle.com/javase/8/docs/api/java/awt/Rectangle.html) |
| [getBounds2D](index.html#624660459%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getBounds2D](index.html#624660459%2FFunctions%2F-134779887)(): [Rectangle2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Rectangle2D.html) |
| [getId](../../it.unibo.alchemist.model.implementations.obstacles/-rect-obstacle2-d/index.html#-1192365972%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getId](../../it.unibo.alchemist.model.implementations.obstacles/-rect-obstacle2-d/index.html#-1192365972%2FFunctions%2F-134779887)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getPathIterator](index.html#-997667124%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getPathIterator](index.html#-997667124%2FFunctions%2F-134779887)(p: [AffineTransform](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/AffineTransform.html)): [PathIterator](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/PathIterator.html) |
| [intersects](index.html#297445569%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [intersects](index.html#297445569%2FFunctions%2F-134779887)(p: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), p1: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), p2: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), p3: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [nearestIntersection](index.html#-1089506749%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [nearestIntersection](index.html#-1089506749%2FFunctions%2F-134779887)(p: [V](index.html), p1: [V](index.html)): [V](index.html) |
| [next](index.html#-1797662097%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [next](index.html#-1797662097%2FFunctions%2F-134779887)(p: [V](index.html), p1: [V](index.html)): [V](index.html) |


## Inheritors


| Name |
|---|
| [RectObstacle2D](../../it.unibo.alchemist.model.implementations.obstacles/-rect-obstacle2-d/index.html) |


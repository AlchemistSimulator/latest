---
title: PointAdapter
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.wormhole.implementation](../index.html)/[PointAdapter](index.html)



# PointAdapter



[jvm]\
class [PointAdapter](index.html)<[P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)>?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Adapts various representations of bidimensional positions.



## Parameters


jvm

| | |
|---|---|
| <P> | position type |



## Functions


| Name | Summary |
|---|---|
| [diff](diff.html) | [jvm]<br>open fun [diff](diff.html)(op: [PointAdapter](index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [PointAdapter](index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)><br>the [PointAdapter](index.html) to sum |
| [equals](equals.html) | [jvm]<br>open fun [equals](equals.html)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [from](from.html) | [jvm]<br>open fun <[P](from.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)>?> [from](from.html)(p: [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [PointAdapter](index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)><br>open fun <[P](from.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)>?> [from](from.html)(p: [Point2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Point2D.html)): [PointAdapter](index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)><br>Builds a [PointAdapter](index.html).<br>[jvm]<br>open fun <[P](from.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)>?> [from](from.html)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [PointAdapter](index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)><br>Builds a [PointAdapter](index.html) from coordinates. |
| [hashCode](hash-code.html) | [jvm]<br>open fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [sum](sum.html) | [jvm]<br>open fun [sum](sum.html)(op: [PointAdapter](index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [PointAdapter](index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)><br>the [PointAdapter](index.html) to sum |
| [toPoint](to-point.html) | [jvm]<br>open fun [toPoint](to-point.html)(): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>the [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) view of this [PointAdapter](index.html) |
| [toPoint2D](to-point2-d.html) | [jvm]<br>open fun [toPoint2D](to-point2-d.html)(): [Point2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Point2D.html)<br>the [Point2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Point2D.html) view of this [PointAdapter](index.html) |
| [toPosition](to-position.html) | [jvm]<br>open fun [toPosition](to-position.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)>): [P](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<br>the environment |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Properties


| Name | Summary |
|---|---|
| [x](x.html) | [jvm]<br>private val [x](x.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [y](y.html) | [jvm]<br>private val [y](y.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |


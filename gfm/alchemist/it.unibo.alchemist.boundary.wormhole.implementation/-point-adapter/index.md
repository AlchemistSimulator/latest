//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.wormhole.implementation](../index.md)/[PointAdapter](index.md)

# PointAdapter

[jvm]\
class [PointAdapter](index.md)<[P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](index.md)>?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Adapts various representations of bidimensional positions.

## Parameters

jvm

| | |
|---|---|
| <P> | position type |

## Functions

| Name | Summary |
|---|---|
| [diff](diff.md) | [jvm]<br>open fun [diff](diff.md)(op: [PointAdapter](index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [PointAdapter](index.md)<[P](index.md)><br>the [PointAdapter](index.md) to sum |
| [equals](equals.md) | [jvm]<br>open fun [equals](equals.md)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [from](from.md) | [jvm]<br>open fun <[P](from.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](index.md)>?> [from](from.md)(p: [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [PointAdapter](index.md)<[P](index.md)><br>open fun <[P](from.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](index.md)>?> [from](from.md)(p: [Point2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Point2D.html)): [PointAdapter](index.md)<[P](index.md)><br>Builds a [PointAdapter](index.md).<br>[jvm]<br>open fun <[P](from.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](index.md)>?> [from](from.md)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [PointAdapter](index.md)<[P](index.md)><br>Builds a [PointAdapter](index.md) from coordinates. |
| [hashCode](hash-code.md) | [jvm]<br>open fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [sum](sum.md) | [jvm]<br>open fun [sum](sum.md)(op: [PointAdapter](index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [PointAdapter](index.md)<[P](index.md)><br>the [PointAdapter](index.md) to sum |
| [toPoint](to-point.md) | [jvm]<br>open fun [toPoint](to-point.md)(): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>the [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) view of this [PointAdapter](index.md) |
| [toPoint2D](to-point2-d.md) | [jvm]<br>open fun [toPoint2D](to-point2-d.md)(): [Point2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Point2D.html)<br>the [Point2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Point2D.html) view of this [PointAdapter](index.md) |
| [toPosition](to-position.md) | [jvm]<br>open fun [toPosition](to-position.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](index.md)>): [P](index.md)<br>the environment |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

## Properties

| Name | Summary |
|---|---|
| [x](x.md) | [jvm]<br>private val [x](x.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [y](y.md) | [jvm]<br>private val [y](y.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |

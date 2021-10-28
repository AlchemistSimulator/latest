//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.wormhole.implementation](../index.md)/[DoubleDimension](index.md)

# DoubleDimension

[jvm]\
class [DoubleDimension](index.md) : [Dimension2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Dimension2D.html)

Implementation of the [Dimension2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Dimension2D.html) abstract class with double precision.

## Constructors

| | |
|---|---|
| [DoubleDimension](-double-dimension.md) | [jvm]<br>open fun [DoubleDimension](-double-dimension.md)()<br>Initializes a new DoubleDimension instance with both width and height set to zero. |
| [DoubleDimension](-double-dimension.md) | [jvm]<br>open fun [DoubleDimension](-double-dimension.md)(d: [Dimension2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Dimension2D.html))<br>Initializes a new DoubleDimension instance using another [Dimension2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Dimension2D.html) object's data. |
| [DoubleDimension](-double-dimension.md) | [jvm]<br>open fun [DoubleDimension](-double-dimension.md)(w: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), h: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Initializes a new DoubleDimension using raw data. |
| [DoubleDimension](-double-dimension.md) | [jvm]<br>open fun [DoubleDimension](-double-dimension.md)(d: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>)<br>Initializes a new DoubleDimension through an array of numbers. |

## Functions

| Name | Summary |
|---|---|
| [clone](index.md#1202578382%2FFunctions%2F-267951372) | [jvm]<br>open fun [clone](index.md#1202578382%2FFunctions%2F-267951372)(): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html) |
| [getHeight](index.md#-88011250%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getHeight](index.md#-88011250%2FFunctions%2F-267951372)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getWidth](index.md#-933061601%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getWidth](index.md#-933061601%2FFunctions%2F-267951372)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [setSize](set-size.md) | [jvm]<br>open fun [setSize](set-size.md)(w: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), h: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [height](height.md) | [jvm]<br>private open val [height](height.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [width](width.md) | [jvm]<br>private open val [width](width.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |

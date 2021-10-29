---
title: DoubleDimension
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.wormhole.implementation](../index.html)/[DoubleDimension](index.html)



# DoubleDimension



[jvm]\
class [DoubleDimension](index.html) : [Dimension2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Dimension2D.html)

Implementation of the [Dimension2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Dimension2D.html) abstract class with double precision.



## Constructors


| | |
|---|---|
| [DoubleDimension](-double-dimension.html) | [jvm]<br>open fun [DoubleDimension](-double-dimension.html)()<br>Initializes a new DoubleDimension instance with both width and height set to zero. |
| [DoubleDimension](-double-dimension.html) | [jvm]<br>open fun [DoubleDimension](-double-dimension.html)(d: [Dimension2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Dimension2D.html))<br>Initializes a new DoubleDimension instance using another [Dimension2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Dimension2D.html) object's data. |
| [DoubleDimension](-double-dimension.html) | [jvm]<br>open fun [DoubleDimension](-double-dimension.html)(w: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), h: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Initializes a new DoubleDimension using raw data. |
| [DoubleDimension](-double-dimension.html) | [jvm]<br>open fun [DoubleDimension](-double-dimension.html)(d: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>)<br>Initializes a new DoubleDimension through an array of numbers. |


## Functions


| Name | Summary |
|---|---|
| [clone](index.html#1202578382%2FFunctions%2F-134779887) | [jvm]<br>open fun [clone](index.html#1202578382%2FFunctions%2F-134779887)(): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html) |
| [getHeight](index.html#-88011250%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getHeight](index.html#-88011250%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getWidth](index.html#-933061601%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getWidth](index.html#-933061601%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [setSize](set-size.html) | [jvm]<br>open fun [setSize](set-size.html)(w: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), h: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [height](height.html) | [jvm]<br>private open val [height](height.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [width](width.html) | [jvm]<br>private open val [width](width.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |


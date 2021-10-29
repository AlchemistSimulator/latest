---
title: DoubleDimension
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.wormhole.implementation](../index.html)/[DoubleDimension](index.html)/[DoubleDimension](-double-dimension.html)



# DoubleDimension



[jvm]\
open fun [DoubleDimension](-double-dimension.html)()



Initializes a new DoubleDimension instance with both width and height set to zero.





[jvm]\
open fun [DoubleDimension](-double-dimension.html)(d: [Dimension2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Dimension2D.html))



Initializes a new DoubleDimension instance using another [Dimension2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Dimension2D.html) object's data. No side effects.



## Parameters


jvm

| | |
|---|---|
| d | is the objects used to get the data |





[jvm]\
open fun [DoubleDimension](-double-dimension.html)(w: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), h: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))



Initializes a new DoubleDimension using raw data.



## Parameters


jvm

| | |
|---|---|
| w | is the double containing the width |
| h | is the double containing the height |





[jvm]\
open fun [DoubleDimension](-double-dimension.html)(d: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>)



Initializes a new DoubleDimension through an array of numbers. d[0] is width, d[1] is height, other elements will be ignored.



## Parameters


jvm

| | |
|---|---|
| d | is a mono-dimensional array of [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html). |





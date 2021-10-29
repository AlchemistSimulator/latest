---
title: RangedDoubleProperty
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.view.properties](../index.html)/[RangedDoubleProperty](index.html)/[RangedDoubleProperty](-ranged-double-property.html)



# RangedDoubleProperty



[jvm]\




@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()



fun [RangedDoubleProperty](-ranged-double-property.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), initialValue: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, lowerBound: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = -Double.MAX_VALUE, upperBound: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = Double.MAX_VALUE)



Based on constructor of DoubleProperty, adds the specified bounds.



## Parameters


jvm

| | |
|---|---|
| name | the name of this property |
| initialValue | the initial value of the wrapped value, defaults to 0.0 |
| lowerBound | the lower bound for the wrapped value to be considered acceptable, defaults to -[Double.MAX_VALUE](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/-m-a-x_-v-a-l-u-e.html) |
| upperBound | the upper bound for the wrapped value to be considered acceptable, defaults to [Double.MAX_VALUE](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/-m-a-x_-v-a-l-u-e.html) |





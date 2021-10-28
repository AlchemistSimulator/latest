---
title: BiomolGradientLayer
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.layers](../index.html)/[BiomolGradientLayer](index.html)/[BiomolGradientLayer](-biomol-gradient-layer.html)



# BiomolGradientLayer



[jvm]\
open fun [BiomolGradientLayer](-biomol-gradient-layer.html)(directionX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), directionY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), unitVariation: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), offset: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))



Initialize a gradient layer which grows in concentration proportionally in space.



## Parameters


jvm

| | |
|---|---|
| directionX | x coordinate of the vector representing the direction in which the gradient grows |
| directionY | y coordinate of the vector representing the direction in which the gradient grows |
| unitVariation | unit variation of the gradient |
| offset | minimum value of concentration reached by this spatial distribution |





[jvm]\
open fun [BiomolGradientLayer](-biomol-gradient-layer.html)(direction: [P](index.html), unitVariation: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), offset: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))



Initialize a gradient layer which grows in concentration proportionally in space.



## Parameters


jvm

| | |
|---|---|
| direction | the [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html) representing the direction in which the gradient grows (here the positions is considered as a vector) |
| unitVariation | unit variation of the gradient |
| offset | minimum value of concentration reached by this spatial distribution |





---
title: BiomolGradientLayer
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.layers](../index.html)/[BiomolGradientLayer](index.html)



# BiomolGradientLayer



[jvm]\
class [BiomolGradientLayer](index.html)<[P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](index.html)>?> : [Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), [P](index.html)> 

A [Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.html) representing a linear distribution in space of a molecule.



## Parameters


jvm

| | |
|---|---|
| <P> | [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html) type |



## Constructors


| | |
|---|---|
| [BiomolGradientLayer](-biomol-gradient-layer.html) | [jvm]<br>open fun [BiomolGradientLayer](-biomol-gradient-layer.html)(directionX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), directionY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), unitVariation: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), offset: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Initialize a gradient layer which grows in concentration proportionally in space. |
| [BiomolGradientLayer](-biomol-gradient-layer.html) | [jvm]<br>open fun [BiomolGradientLayer](-biomol-gradient-layer.html)(direction: [P](index.html), unitVariation: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), offset: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Initialize a gradient layer which grows in concentration proportionally in space. |


## Functions


| Name | Summary |
|---|---|
| [getParameters](get-parameters.html) | [jvm]<br>open fun [getParameters](get-parameters.html)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)><br>the parameters describing this spatial distribution, that's actually a plain. |
| [getValue](get-value.html) | [jvm]<br>open fun [getValue](get-value.html)(p: [P](index.html)): [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html) |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Properties


| Name | Summary |
|---|---|
| [steep](steep.html) | [jvm]<br>private val [steep](steep.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |


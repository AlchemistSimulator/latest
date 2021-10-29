---
title: StepLayer
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.layers](../index.html)/[StepLayer](index.html)



# StepLayer



[jvm]\
class [StepLayer](index.html)<[T](index.html), [P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.model.interfaces/-route/index.html)>?> : [Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.html)<[T](index.html), [P](../../it.unibo.alchemist.model.interfaces/-route/index.html)> 

Implements a [Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.html) with a discontinue spatial distribution: the plane is divided in two parts, both with a constant concentration but with a different in value.



## Parameters


jvm

| | |
|---|---|
| <T> | the type describing the concentration in this [Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.html). |
| <P> | [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html) type. |



## Constructors


| | |
|---|---|
| [StepLayer](-step-layer.html) | [jvm]<br>open fun [StepLayer](-step-layer.html)(mx: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), my: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maxValue: [T](index.html), minValue: [T](index.html))<br>Initialize a [StepLayer](index.html). |
| [StepLayer](-step-layer.html) | [jvm]<br>open fun [StepLayer](-step-layer.html)(maxValue: [T](index.html), minValue: [T](index.html))<br>Initialize a [StepLayer](index.html) where concentration is at its maximum value in first quadrant (for positive values of x and y). |


## Functions


| Name | Summary |
|---|---|
| [getValue](get-value.html) | [jvm]<br>open fun [getValue](get-value.html)(p: [P](../../it.unibo.alchemist.model.interfaces/-route/index.html)): [T](index.html) |


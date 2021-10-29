//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.layers](../index.md)/[StepLayer](index.md)

# StepLayer

[jvm]\
class [StepLayer](index.md)<[T](index.md), [P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../../it.unibo.alchemist.model.interfaces/-route/index.md)>?> : [Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.md)<[T](index.md), [P](../../it.unibo.alchemist.model.interfaces/-route/index.md)> 

Implements a [Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.md) with a discontinue spatial distribution: the plane is divided in two parts, both with a constant concentration but with a different in value.

## Parameters

jvm

| | |
|---|---|
| <T> | the type describing the concentration in this [Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.md). |
| <P> | [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md) type. |

## Constructors

| | |
|---|---|
| [StepLayer](-step-layer.md) | [jvm]<br>open fun [StepLayer](-step-layer.md)(mx: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), my: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maxValue: [T](index.md), minValue: [T](index.md))<br>Initialize a [StepLayer](index.md). |
| [StepLayer](-step-layer.md) | [jvm]<br>open fun [StepLayer](-step-layer.md)(maxValue: [T](index.md), minValue: [T](index.md))<br>Initialize a [StepLayer](index.md) where concentration is at its maximum value in first quadrant (for positive values of x and y). |

## Functions

| Name | Summary |
|---|---|
| [getValue](get-value.md) | [jvm]<br>open fun [getValue](get-value.md)(p: [P](../../it.unibo.alchemist.model.interfaces/-route/index.md)): [T](index.md) |

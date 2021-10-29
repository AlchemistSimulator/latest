//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.layers](../index.md)/[StepLayer](index.md)/[StepLayer](-step-layer.md)

# StepLayer

[jvm]\
open fun [StepLayer](-step-layer.md)(mx: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), my: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maxValue: [T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md), minValue: [T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md))

Initialize a [StepLayer](index.md).

## Parameters

jvm

| | |
|---|---|
| mx | the x value above which the concentration in layer is at its maximum value |
| my | the y value above which the concentration in layer is at its maximum value |
| minValue | the low value of concentration. |
| maxValue | the high value of concentration. |

[jvm]\
open fun [StepLayer](-step-layer.md)(maxValue: [T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md), minValue: [T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md))

Initialize a [StepLayer](index.md) where concentration is at its maximum value in first quadrant (for positive values of x and y).

## Parameters

jvm

| | |
|---|---|
| maxValue | minValue the low value of concentration. |
| minValue | maxValue the high value of concentration. |

---
title: StepLayer
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.layers](../index.html)/[StepLayer](index.html)/[StepLayer](-step-layer.html)



# StepLayer



[jvm]\
open fun [StepLayer](-step-layer.html)(mx: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), my: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maxValue: [T](../-uniform-layer/index.html), minValue: [T](../-uniform-layer/index.html))



Initialize a [StepLayer](index.html).



## Parameters


jvm

| | |
|---|---|
| mx | the x value above which the concentration in layer is at its maximum value |
| my | the y value above which the concentration in layer is at its maximum value |
| minValue | the low value of concentration. |
| maxValue | the high value of concentration. |





[jvm]\
open fun [StepLayer](-step-layer.html)(maxValue: [T](../-uniform-layer/index.html), minValue: [T](../-uniform-layer/index.html))



Initialize a [StepLayer](index.html) where concentration is at its maximum value in first quadrant (for positive values of x and y).



## Parameters


jvm

| | |
|---|---|
| maxValue | minValue the low value of concentration. |
| minValue | maxValue the high value of concentration. |





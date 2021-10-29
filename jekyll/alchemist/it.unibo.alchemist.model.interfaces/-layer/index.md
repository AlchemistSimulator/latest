---
title: Layer
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Layer](index.html)



# Layer



[jvm]\
@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()



interface [Layer](index.html)<[T](index.html), [P](index.html) : [Position](../-position/index.html)<out [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Interface for static layer, containing a substance or a molecule with a spatial distribution.



## Parameters


jvm

| | |
|---|---|
| <T> | the value that measure the substance in a point. |
| <P> | Concentration type |



## Functions


| Name | Summary |
|---|---|
| [getValue](get-value.html) | [jvm]<br>abstract fun [getValue](get-value.html)(p: [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)): [T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)<br>the [Position](../-position/index.html). |


## Inheritors


| Name |
|---|
| [UniformLayer](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html) |
| [StepLayer](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html) |
| [BidimensionalGaussianLayer](../../it.unibo.alchemist.model.implementations.layers/-bidimensional-gaussian-layer/index.html) |
| [BiomolGradientLayer](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html) |


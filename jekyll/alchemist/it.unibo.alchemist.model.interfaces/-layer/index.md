---
title: Layer
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Layer](index.html)



# Layer



[jvm]\
@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()



interface [Layer](index.html)<[T](index.html), [P](index.html) : [Position](../-position/index.html)<out [P](../-position2-d/index.html)>?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

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
| [getValue](get-value.html) | [jvm]<br>abstract fun [getValue](get-value.html)(p: [P](../-position2-d/index.html)): [T](../-node/index.html)<br>the [Position](../-position/index.html). |


## Inheritors


| Name |
|---|
| [UniformLayer](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html) |
| [StepLayer](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html) |
| [BidimensionalGaussianLayer](../../it.unibo.alchemist.model.implementations.layers/-bidimensional-gaussian-layer/index.html) |
| [BiomolGradientLayer](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html) |


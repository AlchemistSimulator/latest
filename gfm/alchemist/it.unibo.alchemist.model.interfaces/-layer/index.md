//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Layer](index.md)

# Layer

[jvm]\
@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()

interface [Layer](index.md)<[T](index.md), [P](index.md) : [Position](../-position/index.md)<out [P](../-incarnation/index.md)>?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

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
| [getValue](get-value.md) | [jvm]<br>abstract fun [getValue](get-value.md)(p: [P](../-incarnation/index.md)): [T](../-node/index.md)<br>the [Position](../-position/index.md). |

## Inheritors

| Name |
|---|
| [UniformLayer](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.md) |
| [StepLayer](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md) |
| [BidimensionalGaussianLayer](../../it.unibo.alchemist.model.implementations.layers/-bidimensional-gaussian-layer/index.md) |
| [BiomolGradientLayer](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.md) |

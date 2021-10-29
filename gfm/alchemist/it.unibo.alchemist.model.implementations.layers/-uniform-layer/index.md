//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.layers](../index.md)/[UniformLayer](index.md)

# UniformLayer

[jvm]\
class [UniformLayer](index.md)<[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<out [P](../../it.unibo.alchemist.model.interfaces/-route/index.md)>?> : [Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.md)<[T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md), [P](../../it.unibo.alchemist.model.interfaces/-route/index.md)> 

a Layer where the concentration is the same at every point in space.

## Parameters

jvm

| | |
|---|---|
| <P> | position type |
| <T> | concentration type |

## Constructors

| | |
|---|---|
| [UniformLayer](-uniform-layer.md) | [jvm]<br>open fun [UniformLayer](-uniform-layer.md)(level: [T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md))<br>the concentration |

## Functions

| Name | Summary |
|---|---|
| [getValue](get-value.md) | [jvm]<br>open fun [getValue](get-value.md)(p: [P](../../it.unibo.alchemist.model.interfaces/-route/index.md)): [T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md) |

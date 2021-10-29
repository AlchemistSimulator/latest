---
title: UniformLayer
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.layers](../index.html)/[UniformLayer](index.html)



# UniformLayer



[jvm]\
class [UniformLayer](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](../../it.unibo.alchemist.model.interfaces/-route/index.html)>?> : [Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.html)<[T](../-step-layer/index.html), [P](../../it.unibo.alchemist.model.interfaces/-route/index.html)> 

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
| [UniformLayer](-uniform-layer.html) | [jvm]<br>open fun [UniformLayer](-uniform-layer.html)(level: [T](../-step-layer/index.html))<br>the concentration |


## Functions


| Name | Summary |
|---|---|
| [getValue](get-value.html) | [jvm]<br>open fun [getValue](get-value.html)(p: [P](../../it.unibo.alchemist.model.interfaces/-route/index.html)): [T](../-step-layer/index.html) |


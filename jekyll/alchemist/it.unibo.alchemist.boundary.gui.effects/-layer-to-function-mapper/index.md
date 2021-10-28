---
title: LayerToFunctionMapper
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.effects](../index.html)/[LayerToFunctionMapper](index.html)



# LayerToFunctionMapper



[jvm]\
interface [LayerToFunctionMapper](index.html)

Defines an object capable of mapping a Layer<T, P> to a Function<* in P, * out Number>.



## Functions


| Name | Summary |
|---|---|
| [map](map.html) | [jvm]<br>abstract fun <[T](map.html), [P](map.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](map.html)>> [map](map.html)(layers: [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.html)<[T](map.html), [P](map.html)>>): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[Function](https://docs.oracle.com/javase/8/docs/api/java/util/function/Function.html)<in [P](map.html), out [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>><br>see [LayerToFunctionMapper.map](map.html).<br>[jvm]<br>abstract fun <[T](map.html), [P](map.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](map.html)>> [map](map.html)(layers: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.html)<[T](map.html), [P](map.html)>>): [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[Function](https://docs.oracle.com/javase/8/docs/api/java/util/function/Function.html)<in [P](map.html), out [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>><br>Effectively map the given layers, layers may be filtered too if the mapper is only able to map certain types of layers. |
| [prepare](prepare.html) | [jvm]<br>open fun <[T](prepare.html), [P](prepare.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](prepare.html)>> [prepare](prepare.html)(effect: [DrawLayersValues](../-draw-layers-values/index.html), toDraw: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.html)<[T](prepare.html), [P](prepare.html)>>, env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](prepare.html), [P](prepare.html)>, g: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](prepare.html)>)<br>Prepare the mapping (if necessary). |


## Inheritors


| Name |
|---|
| [BidimensionalGaussianLayersMapper](../-bidimensional-gaussian-layers-mapper/index.html) |


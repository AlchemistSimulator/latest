---
title: BidimensionalGaussianLayersMapper
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.effects](../index.html)/[BidimensionalGaussianLayersMapper](index.html)



# BidimensionalGaussianLayersMapper



[jvm]\
class [BidimensionalGaussianLayersMapper](index.html) : [LayerToFunctionMapper](../-layer-to-function-mapper/index.html)

Maps [BidimensionalGaussianLayer](../../it.unibo.alchemist.model.implementations.layers/-bidimensional-gaussian-layer/index.html)s, it ignores any other layer.



This class also manages to infer optimal min and max layer values automatically so the user does not have to set them by hand.



## Constructors


| | |
|---|---|
| [BidimensionalGaussianLayersMapper](-bidimensional-gaussian-layers-mapper.html) | [jvm]<br>fun [BidimensionalGaussianLayersMapper](-bidimensional-gaussian-layers-mapper.html)() |


## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [map](map.html) | [jvm]<br>open override fun <[T](map.html), [P](map.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](map.html)>> [map](map.html)(layers: [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.html)<[T](map.html), [P](map.html)>>): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[Function](https://docs.oracle.com/javase/8/docs/api/java/util/function/Function.html)<in [P](map.html), out [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>><br>see [LayerToFunctionMapper.map](../-layer-to-function-mapper/map.html).<br>[jvm]<br>open override fun <[T](map.html), [P](map.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](map.html)>> [map](map.html)(layers: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.html)<[T](map.html), [P](map.html)>>): [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[Function](https://docs.oracle.com/javase/8/docs/api/java/util/function/Function.html)<in [P](map.html), out [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>><br>Effectively map the given layers, layers may be filtered too if the mapper is only able to map certain types of layers. |
| [prepare](prepare.html) | [jvm]<br>open override fun <[T](prepare.html), [P](prepare.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](prepare.html)>> [prepare](prepare.html)(effect: [DrawLayersValues](../-draw-layers-values/index.html), toDraw: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.html)<[T](prepare.html), [P](prepare.html)>>, env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](prepare.html), [P](prepare.html)>, g: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](prepare.html)>)<br>Prepare the mapping (if necessary). |


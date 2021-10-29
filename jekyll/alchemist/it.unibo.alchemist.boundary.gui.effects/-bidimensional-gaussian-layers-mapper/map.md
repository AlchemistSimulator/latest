---
title: map
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.effects](../index.html)/[BidimensionalGaussianLayersMapper](index.html)/[map](map.html)



# map



[jvm]\
open override fun <[T](map.html), [P](map.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](map.html)>> [map](map.html)(layers: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.html)<[T](map.html), [P](map.html)>>): [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[Function](https://docs.oracle.com/javase/8/docs/api/java/util/function/Function.html)<in [P](map.html), out [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>>



Effectively map the given layers, layers may be filtered too if the mapper is only able to map certain types of layers.





[jvm]\
open override fun <[T](map.html), [P](map.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](map.html)>> [map](map.html)(layers: [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.html)<[T](map.html), [P](map.html)>>): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[Function](https://docs.oracle.com/javase/8/docs/api/java/util/function/Function.html)<in [P](map.html), out [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>>



see [LayerToFunctionMapper.map](../-layer-to-function-mapper/map.html).





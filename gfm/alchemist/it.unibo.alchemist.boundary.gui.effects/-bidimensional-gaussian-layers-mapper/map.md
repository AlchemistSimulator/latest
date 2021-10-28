//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.effects](../index.md)/[BidimensionalGaussianLayersMapper](index.md)/[map](map.md)

# map

[jvm]\
open override fun <[T](map.md), [P](map.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](map.md)>> [map](map.md)(layers: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.md)<[T](map.md), [P](map.md)>>): [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[Function](https://docs.oracle.com/javase/8/docs/api/java/util/function/Function.html)<in [P](map.md), out [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>>

Effectively map the given layers, layers may be filtered too if the mapper is only able to map certain types of layers.

[jvm]\
open override fun <[T](map.md), [P](map.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](map.md)>> [map](map.md)(layers: [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.md)<[T](map.md), [P](map.md)>>): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[Function](https://docs.oracle.com/javase/8/docs/api/java/util/function/Function.html)<in [P](map.md), out [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>>

see [LayerToFunctionMapper.map](../-layer-to-function-mapper/map.md).

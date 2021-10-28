//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.effects](../index.md)/[BidimensionalGaussianLayersMapper](index.md)

# BidimensionalGaussianLayersMapper

[jvm]\
class [BidimensionalGaussianLayersMapper](index.md) : [LayerToFunctionMapper](../-layer-to-function-mapper/index.md)

Maps [BidimensionalGaussianLayer](../../it.unibo.alchemist.model.implementations.layers/-bidimensional-gaussian-layer/index.md)s, it ignores any other layer.

This class also manages to infer optimal min and max layer values automatically so the user does not have to set them by hand.

## Constructors

| | |
|---|---|
| [BidimensionalGaussianLayersMapper](-bidimensional-gaussian-layers-mapper.md) | [jvm]<br>fun [BidimensionalGaussianLayersMapper](-bidimensional-gaussian-layers-mapper.md)() |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [jvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [map](map.md) | [jvm]<br>open override fun <[T](map.md), [P](map.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](map.md)>> [map](map.md)(layers: [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.md)<[T](map.md), [P](map.md)>>): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[Function](https://docs.oracle.com/javase/8/docs/api/java/util/function/Function.html)<in [P](map.md), out [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>><br>see [LayerToFunctionMapper.map](../-layer-to-function-mapper/map.md).<br>[jvm]<br>open override fun <[T](map.md), [P](map.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](map.md)>> [map](map.md)(layers: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.md)<[T](map.md), [P](map.md)>>): [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[Function](https://docs.oracle.com/javase/8/docs/api/java/util/function/Function.html)<in [P](map.md), out [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>><br>Effectively map the given layers, layers may be filtered too if the mapper is only able to map certain types of layers. |
| [prepare](prepare.md) | [jvm]<br>open override fun <[T](prepare.md), [P](prepare.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](prepare.md)>> [prepare](prepare.md)(effect: [DrawLayersValues](../-draw-layers-values/index.md), toDraw: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.md)<[T](prepare.md), [P](prepare.md)>>, env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](prepare.md), [P](prepare.md)>, g: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)<[P](prepare.md)>)<br>Prepare the mapping (if necessary). |

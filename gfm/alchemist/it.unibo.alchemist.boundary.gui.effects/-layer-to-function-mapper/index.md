//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.effects](../index.md)/[LayerToFunctionMapper](index.md)

# LayerToFunctionMapper

[jvm]\
interface [LayerToFunctionMapper](index.md)

Defines an object capable of mapping a Layer<T, P> to a Function<* in P, * out Number>.

## Functions

| Name | Summary |
|---|---|
| [map](map.md) | [jvm]<br>abstract fun <[T](map.md), [P](map.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](map.md)>> [map](map.md)(layers: [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.md)<[T](map.md), [P](map.md)>>): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[Function](https://docs.oracle.com/javase/8/docs/api/java/util/function/Function.html)<in [P](map.md), out [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>><br>see [LayerToFunctionMapper.map](map.md).<br>[jvm]<br>abstract fun <[T](map.md), [P](map.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](map.md)>> [map](map.md)(layers: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.md)<[T](map.md), [P](map.md)>>): [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[Function](https://docs.oracle.com/javase/8/docs/api/java/util/function/Function.html)<in [P](map.md), out [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>><br>Effectively map the given layers, layers may be filtered too if the mapper is only able to map certain types of layers. |
| [prepare](prepare.md) | [jvm]<br>open fun <[T](prepare.md), [P](prepare.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](prepare.md)>> [prepare](prepare.md)(effect: [DrawLayersValues](../-draw-layers-values/index.md), toDraw: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.md)<[T](prepare.md), [P](prepare.md)>>, env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](prepare.md), [P](prepare.md)>, g: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)<[P](prepare.md)>)<br>Prepare the mapping (if necessary). |

## Inheritors

| Name |
|---|
| [BidimensionalGaussianLayersMapper](../-bidimensional-gaussian-layers-mapper/index.md) |

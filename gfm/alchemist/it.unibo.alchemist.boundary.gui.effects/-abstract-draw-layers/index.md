//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.effects](../index.md)/[AbstractDrawLayers](index.md)

# AbstractDrawLayers

[jvm]\
abstract class [AbstractDrawLayers](index.md) : [DrawOnce](../-draw-once/index.md), [DrawLayers](../-draw-layers/index.md)

This class collects the following responsibilities: - it manages to draw layers only when necessary (as the apply method will be called for every node). Every subclass must only define the [drawLayers](draw-layers.md) method, which is guaranteed to be called only when necessary. - it declares gui controls for the selection of the color to use - it declares gui controls for the selection of a filter, used to filter the layers to draw. In particular, it allows the user to specify a molecule, meaning that only the layer containing such molecule will be drawn (otherwise the effect is applied to all layers)

## Functions

| Name | Summary |
|---|---|
| [apply](../-draw-once/apply.md) | [jvm]<br>open fun <[T](../-draw-once/apply.md), [P](../-draw-once/apply.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md)>?> [apply](../-draw-once/apply.md)(graphics: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md), [P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md)>, wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)<[P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md)>)<br>@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()<br>~~open~~ ~~fun~~ [~~apply~~](../-effect/apply.md)~~(~~~~graphic~~~~:~~ [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html)~~,~~ ~~node~~~~:~~ [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>~~,~~ ~~x~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~,~~ ~~y~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~)~~<br>open fun <[T](../-effect/apply.md), [P](../-effect/apply.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md)>?> [apply](../-effect/apply.md)(g: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md)>, env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md), [P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md)>, wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)<[P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md)>)<br>Applies the effect. |
| [drawLayers](draw-layers.md) | [jvm]<br>abstract fun <[T](draw-layers.md), [P](draw-layers.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md)>?> [drawLayers](draw-layers.md)(toDraw: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md), [P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md)>>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md), [P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md)>, graphics: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)<[P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md)>)<br>Effectively draw the layers. |
| [equals](../-effect/equals.md) | [jvm]<br>abstract fun [equals](../-effect/equals.md)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getColorSummary](get-color-summary.md) | [jvm]<br>open fun [getColorSummary](get-color-summary.md)(): [Color](https://docs.oracle.com/javase/8/docs/api/java/awt/Color.html) |
| [getMarkerNodeID](../-draw-bidimensional-gaussian-layers-gradient/index.md#470324422%2FFunctions%2F-267951372) | [jvm]<br>@[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()<br>open fun [getMarkerNodeID](../-draw-bidimensional-gaussian-layers-gradient/index.md#470324422%2FFunctions%2F-267951372)(): [Integer](https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html)<br>the marker node id |
| [hashCode](../-effect/hash-code.md) | [jvm]<br>abstract fun [hashCode](../-effect/hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isLayerFilter](is-layer-filter.md) | [jvm]<br>open fun [isLayerFilter](is-layer-filter.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>a boolean representing whether or not layer filter is on |

## Properties

| Name | Summary |
|---|---|
| [alpha](alpha.md) | [jvm]<br>private open var [alpha](alpha.md): RangedInteger |
| [blue](blue.md) | [jvm]<br>private open var [blue](blue.md): RangedInteger |
| [green](green.md) | [jvm]<br>private open var [green](green.md): RangedInteger |
| [layerFilter](layer-filter.md) | [jvm]<br>private open var [layerFilter](layer-filter.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [molString](mol-string.md) | [jvm]<br>private open var [molString](mol-string.md): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [red](red.md) | [jvm]<br>private open var [red](red.md): RangedInteger |

## Inheritors

| Name |
|---|
| [DrawLayersValues](../-draw-layers-values/index.md) |

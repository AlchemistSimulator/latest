---
title: AbstractDrawLayers
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.effects](../index.html)/[AbstractDrawLayers](index.html)



# AbstractDrawLayers



[jvm]\
abstract class [AbstractDrawLayers](index.html) : [DrawOnce](../-draw-once/index.html), [DrawLayers](../-draw-layers/index.html)

This class collects the following responsibilities: - it manages to draw layers only when necessary (as the apply method will be called for every node). Every subclass must only define the [drawLayers](draw-layers.html) method, which is guaranteed to be called only when necessary. - it declares gui controls for the selection of the color to use - it declares gui controls for the selection of a filter, used to filter the layers to draw. In particular, it allows the user to specify a molecule, meaning that only the layer containing such molecule will be drawn (otherwise the effect is applied to all layers)



## Functions


| Name | Summary |
|---|---|
| [apply](../-draw-once/apply.html) | [jvm]<br>open fun <[T](../-draw-once/apply.html), [P](../-draw-once/apply.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>?> [apply](../-draw-once/apply.html)(graphics: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>, wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>)<br>@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()<br>~~open~~ ~~fun~~ [~~apply~~](../-effect/apply.html)~~(~~~~graphic~~~~:~~ [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html)~~,~~ ~~node~~~~:~~ [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>~~,~~ ~~x~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~,~~ ~~y~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~)~~<br>open fun <[T](../-effect/apply.html), [P](../-effect/apply.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>?> [apply](../-effect/apply.html)(g: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html)>, env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>, wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>)<br>Applies the effect. |
| [drawLayers](draw-layers.html) | [jvm]<br>abstract fun <[T](draw-layers.html), [P](draw-layers.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>?> [drawLayers](draw-layers.html)(toDraw: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>, graphics: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>)<br>Effectively draw the layers. |
| [equals](../-effect/equals.html) | [jvm]<br>abstract fun [equals](../-effect/equals.html)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getColorSummary](get-color-summary.html) | [jvm]<br>open fun [getColorSummary](get-color-summary.html)(): [Color](https://docs.oracle.com/javase/8/docs/api/java/awt/Color.html) |
| [getMarkerNodeID](../-draw-bidimensional-gaussian-layers-gradient/index.html#470324422%2FFunctions%2F-134779887) | [jvm]<br>@[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()<br>open fun [getMarkerNodeID](../-draw-bidimensional-gaussian-layers-gradient/index.html#470324422%2FFunctions%2F-134779887)(): [Integer](https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html)<br>the marker node id |
| [hashCode](../-effect/hash-code.html) | [jvm]<br>abstract fun [hashCode](../-effect/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isLayerFilter](is-layer-filter.html) | [jvm]<br>open fun [isLayerFilter](is-layer-filter.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>a boolean representing whether or not layer filter is on |


## Properties


| Name | Summary |
|---|---|
| [alpha](alpha.html) | [jvm]<br>private open var [alpha](alpha.html): RangedInteger |
| [blue](blue.html) | [jvm]<br>private open var [blue](blue.html): RangedInteger |
| [green](green.html) | [jvm]<br>private open var [green](green.html): RangedInteger |
| [layerFilter](layer-filter.html) | [jvm]<br>private open var [layerFilter](layer-filter.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [molString](mol-string.html) | [jvm]<br>private open var [molString](mol-string.html): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [red](red.html) | [jvm]<br>private open var [red](red.html): RangedInteger |


## Inheritors


| Name |
|---|
| [DrawLayersValues](../-draw-layers-values/index.html) |


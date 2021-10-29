//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.effects](../index.md)/[DrawLayers](index.md)

# DrawLayers

[jvm]\
interface [DrawLayers](index.md) : [Effect](../-effect/index.md)

Basic interface for every effect that draws something related to [it.unibo.alchemist.model.interfaces.Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.md)s. This class is a workaround: the [Effect](../-effect/index.md) abstraction is meant to add effects to nodes, not to draw layers. At present, is the finest workaround available. This workaround has the following disadvantages: - when there aren't nodes visible in the gui the effects are not used at all, so this effect won't work.

## Functions

| Name | Summary |
|---|---|
| [apply](../-effect/apply.md) | [jvm]<br>@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()<br>~~open~~ ~~fun~~ [~~apply~~](../-effect/apply.md)~~(~~~~graphic~~~~:~~ [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html)~~,~~ ~~node~~~~:~~ [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>~~,~~ ~~x~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~,~~ ~~y~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~)~~<br>open fun <[T](../-effect/apply.md), [P](../-effect/apply.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.md)>?> [apply](../-effect/apply.md)(g: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md)>, env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.md)>, wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.md)>)<br>Applies the effect. |
| [drawLayers](draw-layers.md) | [jvm]<br>abstract fun <[T](draw-layers.md), [P](draw-layers.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.md)>?> [drawLayers](draw-layers.md)(toDraw: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.md)>>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.md)>, graphics: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.md)>)<br>Effectively draw the layers. |
| [equals](../-effect/equals.md) | [jvm]<br>abstract fun [equals](../-effect/equals.md)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getColorSummary](../-effect/get-color-summary.md) | [jvm]<br>abstract fun [getColorSummary](../-effect/get-color-summary.md)(): [Color](https://docs.oracle.com/javase/8/docs/api/java/awt/Color.html)<br>a color which resembles the color of this effect |
| [hashCode](../-effect/hash-code.md) | [jvm]<br>abstract fun [hashCode](../-effect/hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

## Inheritors

| Name |
|---|
| [AbstractDrawLayers](../-abstract-draw-layers/index.md) |

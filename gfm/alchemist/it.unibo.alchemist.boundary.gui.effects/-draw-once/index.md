//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.effects](../index.md)/[DrawOnce](index.md)

# DrawOnce

[jvm]\
abstract class [DrawOnce](index.md) : [Effect](../-effect/index.md)

Effects are normally applied for each node, this is a base class for effects that do not need to be redrawn for each node. In other words, this effect will be applied for a single node instead of redrawing for all of them.

## Functions

| Name | Summary |
|---|---|
| [apply](apply.md) | [jvm]<br>open fun <[T](apply.md), [P](apply.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.md)>?> [apply](apply.md)(graphics: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.boundary.monitors/-map-display/index.md)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.boundary.monitors/-map-display/index.md), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.md)>, wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.md)>)<br>@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()<br>~~open~~ ~~fun~~ [~~apply~~](../-effect/apply.md)~~(~~~~graphic~~~~:~~ [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html)~~,~~ ~~node~~~~:~~ [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>~~,~~ ~~x~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~,~~ ~~y~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~)~~<br>Applies the effect. |
| [equals](../-effect/equals.md) | [jvm]<br>abstract fun [equals](../-effect/equals.md)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getColorSummary](../-effect/get-color-summary.md) | [jvm]<br>abstract fun [getColorSummary](../-effect/get-color-summary.md)(): [Color](https://docs.oracle.com/javase/8/docs/api/java/awt/Color.html)<br>a color which resembles the color of this effect |
| [hashCode](../-effect/hash-code.md) | [jvm]<br>abstract fun [hashCode](../-effect/hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

## Properties

| Name | Summary |
|---|---|
| [markerNodeID](marker-node-i-d.md) | [jvm]<br>@[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()<br>private open val [markerNodeID](marker-node-i-d.md): [Integer](https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html) |

## Inheritors

| Name |
|---|
| [DrawCognitiveMap](../-draw-cognitive-map/index.md) |
| [DrawNavigationGraph](../-draw-navigation-graph/index.md) |
| [DrawPedestrianPath](../-draw-pedestrian-path/index.md) |
| [AbstractDrawLayers](../-abstract-draw-layers/index.md) |

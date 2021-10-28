---
title: DrawOnce
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.effects](../index.html)/[DrawOnce](index.html)



# DrawOnce



[jvm]\
abstract class [DrawOnce](index.html) : [Effect](../-effect/index.html)

Effects are normally applied for each node, this is a base class for effects that do not need to be redrawn for each node. In other words, this effect will be applied for a single node instead of redrawing for all of them.



## Functions


| Name | Summary |
|---|---|
| [apply](apply.html) | [jvm]<br>open fun <[T](apply.html), [P](apply.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>?> [apply](apply.html)(graphics: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>, wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>)<br>@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()<br>~~open~~ ~~fun~~ [~~apply~~](../-effect/apply.html)~~(~~~~graphic~~~~:~~ [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html)~~,~~ ~~node~~~~:~~ [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>~~,~~ ~~x~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~,~~ ~~y~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~)~~<br>Applies the effect. |
| [equals](../-effect/equals.html) | [jvm]<br>abstract fun [equals](../-effect/equals.html)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getColorSummary](../-effect/get-color-summary.html) | [jvm]<br>abstract fun [getColorSummary](../-effect/get-color-summary.html)(): [Color](https://docs.oracle.com/javase/8/docs/api/java/awt/Color.html)<br>a color which resembles the color of this effect |
| [hashCode](../-effect/hash-code.html) | [jvm]<br>abstract fun [hashCode](../-effect/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |


## Properties


| Name | Summary |
|---|---|
| [markerNodeID](marker-node-i-d.html) | [jvm]<br>@[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()<br>private open val [markerNodeID](marker-node-i-d.html): [Integer](https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html) |


## Inheritors


| Name |
|---|
| [DrawCognitiveMap](../-draw-cognitive-map/index.html) |
| [DrawNavigationGraph](../-draw-navigation-graph/index.html) |
| [DrawPedestrianPath](../-draw-pedestrian-path/index.html) |
| [AbstractDrawLayers](../-abstract-draw-layers/index.html) |


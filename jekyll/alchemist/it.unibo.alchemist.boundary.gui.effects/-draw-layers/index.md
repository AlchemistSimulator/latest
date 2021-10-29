---
title: DrawLayers
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.effects](../index.html)/[DrawLayers](index.html)



# DrawLayers



[jvm]\
interface [DrawLayers](index.html) : [Effect](../-effect/index.html)

Basic interface for every effect that draws something related to [it.unibo.alchemist.model.interfaces.Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.html)s. This class is a workaround: the [Effect](../-effect/index.html) abstraction is meant to add effects to nodes, not to draw layers. At present, is the finest workaround available. This workaround has the following disadvantages: - when there aren't nodes visible in the gui the effects are not used at all, so this effect won't work.



## Functions


| Name | Summary |
|---|---|
| [apply](../-effect/apply.html) | [jvm]<br>@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()<br>~~open~~ ~~fun~~ [~~apply~~](../-effect/apply.html)~~(~~~~graphic~~~~:~~ [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html)~~,~~ ~~node~~~~:~~ [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>~~,~~ ~~x~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~,~~ ~~y~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~)~~<br>open fun <[T](../-effect/apply.html), [P](../-effect/apply.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>?> [apply](../-effect/apply.html)(g: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../-function-drawer/draw-function.html)>, env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../-function-drawer/draw-function.html), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>, wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>)<br>Applies the effect. |
| [drawLayers](draw-layers.html) | [jvm]<br>abstract fun <[T](draw-layers.html), [P](draw-layers.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>?> [drawLayers](draw-layers.html)(toDraw: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.html)<[T](../-function-drawer/draw-function.html), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../-function-drawer/draw-function.html), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>, graphics: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>)<br>Effectively draw the layers. |
| [equals](../-effect/equals.html) | [jvm]<br>abstract fun [equals](../-effect/equals.html)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getColorSummary](../-effect/get-color-summary.html) | [jvm]<br>abstract fun [getColorSummary](../-effect/get-color-summary.html)(): [Color](https://docs.oracle.com/javase/8/docs/api/java/awt/Color.html)<br>a color which resembles the color of this effect |
| [hashCode](../-effect/hash-code.html) | [jvm]<br>abstract fun [hashCode](../-effect/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |


## Inheritors


| Name |
|---|
| [AbstractDrawLayers](../-abstract-draw-layers/index.html) |


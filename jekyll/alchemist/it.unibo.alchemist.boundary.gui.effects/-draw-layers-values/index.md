---
title: DrawLayersValues
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.effects](../index.html)/[DrawLayersValues](index.html)



# DrawLayersValues



[jvm]\
abstract class [DrawLayersValues](index.html) : [AbstractDrawLayers](../-abstract-draw-layers/index.html), [FunctionDrawer](../-function-drawer/index.html)

This is a basic class for all the effects meant to draw [it.unibo.alchemist.model.interfaces.Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.html)s values in different points of the view. One effect could draw isolines, whereas another could represent different values with a gradient. Normally, drawing a layer's values only makes sense for "numerical" layers (i.e. layers for which the values are [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)s). However, one could have a "non-numerical" layer whose [getValue](../../it.unibo.alchemist.model.interfaces/-layer/get-value.html) return type is an object from which a value can be extracted somehow. In the end, drawing a layer's values makes sense as long as there is a way to map those values to Numbers. More generally, a [LayerToFunctionMapper](../-layer-to-function-mapper/index.html) is needed. As this class is not aware of which mapper to use, this responsibility is left to subclasses. When drawing layers values, it can be important to know the min and max layer values that will be drawn. This class declares gui controls that allow the user to specify such boundaries.



## Functions


| Name | Summary |
|---|---|
| [apply](../-draw-once/apply.html) | [jvm]<br>open fun <[T](../-draw-once/apply.html), [P](../-draw-once/apply.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>?> [apply](../-draw-once/apply.html)(graphics: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>, wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>)<br>@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()<br>~~open~~ ~~fun~~ [~~apply~~](../-effect/apply.html)~~(~~~~graphic~~~~:~~ [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html)~~,~~ ~~node~~~~:~~ [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>~~,~~ ~~x~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~,~~ ~~y~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~)~~<br>open fun <[T](../-effect/apply.html), [P](../-effect/apply.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>?> [apply](../-effect/apply.html)(g: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html)>, env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>, wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>)<br>Applies the effect. |
| [drawFunction](draw-function.html) | [jvm]<br>abstract fun <[T](draw-function.html), [P](draw-function.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>?> [drawFunction](draw-function.html)(function: (out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)) -> out [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>, graphics: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>)<br>Draw the provided function. |
| [drawLayers](draw-layers.html) | [jvm]<br>open fun <[T](draw-layers.html), [P](draw-layers.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>?> [drawLayers](draw-layers.html)(toDraw: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>, graphics: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>) |
| [equals](../-effect/equals.html) | [jvm]<br>abstract fun [equals](../-effect/equals.html)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getAlpha](../-draw-bidimensional-gaussian-layers-gradient/index.html#-1609809598%2FFunctions%2F-134779887) | [jvm]<br>open fun [getAlpha](../-draw-bidimensional-gaussian-layers-gradient/index.html#-1609809598%2FFunctions%2F-134779887)(): RangedInteger<br>alpha channel |
| [getBlue](../-draw-bidimensional-gaussian-layers-gradient/index.html#1167250208%2FFunctions%2F-134779887) | [jvm]<br>open fun [getBlue](../-draw-bidimensional-gaussian-layers-gradient/index.html#1167250208%2FFunctions%2F-134779887)(): RangedInteger<br>blue channel |
| [getColorSummary](../-abstract-draw-layers/get-color-summary.html) | [jvm]<br>open fun [getColorSummary](../-abstract-draw-layers/get-color-summary.html)(): [Color](https://docs.oracle.com/javase/8/docs/api/java/awt/Color.html) |
| [getGreen](../-draw-bidimensional-gaussian-layers-gradient/index.html#-1357752515%2FFunctions%2F-134779887) | [jvm]<br>open fun [getGreen](../-draw-bidimensional-gaussian-layers-gradient/index.html#-1357752515%2FFunctions%2F-134779887)(): RangedInteger<br>green channel |
| [getMarkerNodeID](../-draw-bidimensional-gaussian-layers-gradient/index.html#470324422%2FFunctions%2F-134779887) | [jvm]<br>@[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()<br>open fun [getMarkerNodeID](../-draw-bidimensional-gaussian-layers-gradient/index.html#470324422%2FFunctions%2F-134779887)(): [Integer](https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html)<br>the marker node id |
| [getMolString](../-draw-bidimensional-gaussian-layers-gradient/index.html#676927493%2FFunctions%2F-134779887) | [jvm]<br>open fun [getMolString](../-draw-bidimensional-gaussian-layers-gradient/index.html#676927493%2FFunctions%2F-134779887)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>a string representing the current molecule |
| [getRed](../-draw-bidimensional-gaussian-layers-gradient/index.html#997430831%2FFunctions%2F-134779887) | [jvm]<br>open fun [getRed](../-draw-bidimensional-gaussian-layers-gradient/index.html#997430831%2FFunctions%2F-134779887)(): RangedInteger<br>red channel |
| [hashCode](../-effect/hash-code.html) | [jvm]<br>abstract fun [hashCode](../-effect/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isLayerFilter](../-abstract-draw-layers/is-layer-filter.html) | [jvm]<br>open fun [isLayerFilter](../-abstract-draw-layers/is-layer-filter.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>a boolean representing whether or not layer filter is on |
| [setAlpha](../-draw-bidimensional-gaussian-layers-gradient/index.html#-256941374%2FFunctions%2F-134779887) | [jvm]<br>open fun [setAlpha](../-draw-bidimensional-gaussian-layers-gradient/index.html#-256941374%2FFunctions%2F-134779887)(alpha: RangedInteger)<br>alpha channel |
| [setBlue](../-draw-bidimensional-gaussian-layers-gradient/index.html#-354420728%2FFunctions%2F-134779887) | [jvm]<br>open fun [setBlue](../-draw-bidimensional-gaussian-layers-gradient/index.html#-354420728%2FFunctions%2F-134779887)(blue: RangedInteger)<br>blue channel |
| [setGreen](../-draw-bidimensional-gaussian-layers-gradient/index.html#2124109629%2FFunctions%2F-134779887) | [jvm]<br>open fun [setGreen](../-draw-bidimensional-gaussian-layers-gradient/index.html#2124109629%2FFunctions%2F-134779887)(green: RangedInteger)<br>green channel |
| [setLayerFilter](../-draw-bidimensional-gaussian-layers-gradient/index.html#792349975%2FFunctions%2F-134779887) | [jvm]<br>open fun [setLayerFilter](../-draw-bidimensional-gaussian-layers-gradient/index.html#792349975%2FFunctions%2F-134779887)(layerFilter: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>a boolean representing whether or not layer filter must be on |
| [setMolString](../-draw-bidimensional-gaussian-layers-gradient/index.html#-2103088628%2FFunctions%2F-134779887) | [jvm]<br>open fun [setMolString](../-draw-bidimensional-gaussian-layers-gradient/index.html#-2103088628%2FFunctions%2F-134779887)(molString: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>a string representing the molecule to use |
| [setRed](../-draw-bidimensional-gaussian-layers-gradient/index.html#1704630319%2FFunctions%2F-134779887) | [jvm]<br>open fun [setRed](../-draw-bidimensional-gaussian-layers-gradient/index.html#1704630319%2FFunctions%2F-134779887)(red: RangedInteger)<br>red channel |


## Properties


| Name | Summary |
|---|---|
| [maxLayerValue](max-layer-value.html) | [jvm]<br>private open var [maxLayerValue](max-layer-value.html): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [minLayerValue](min-layer-value.html) | [jvm]<br>private open var [minLayerValue](min-layer-value.html): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Inheritors


| Name |
|---|
| [DrawLayersIsolines](../-draw-layers-isolines/index.html) |
| [DrawLayersGradient](../-draw-layers-gradient/index.html) |


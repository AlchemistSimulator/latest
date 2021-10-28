---
title: DrawLayersIsolines
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.effects](../index.html)/[DrawLayersIsolines](index.html)



# DrawLayersIsolines



[jvm]\
abstract class [DrawLayersIsolines](index.html) : [DrawLayersValues](../-draw-layers-values/index.html)

Draw layers isolines. The user must specify: - the number of isolines to draw - the min layer value - the max layer value - the distribution, used to space isoline values between min and max This class defines the drawFunction method, which is capable of drawing a layer's isolines given a function. The only responsibility left to subclasses is to provide a [LayerToFunctionMapper](../-layer-to-function-mapper/index.html).



## Constructors


| | |
|---|---|
| [DrawLayersIsolines](-draw-layers-isolines.html) | [jvm]<br>open fun [DrawLayersIsolines](-draw-layers-isolines.html)(algorithm: [IsolinesFinder](../../it.unibo.alchemist.boundary.gui.isolines/-isolines-finder/index.html))<br>Every class extending this one should call this constructor. |


## Types


| Name | Summary |
|---|---|
| [Distribution](-distribution/index.html) | [jvm]<br>enum [Distribution](-distribution/index.html)<br>Distributions describing how values within an interval should be spaced. |


## Functions


| Name | Summary |
|---|---|
| [apply](../-draw-once/apply.html) | [jvm]<br>open fun <[T](../-draw-once/apply.html), [P](../-draw-once/apply.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>?> [apply](../-draw-once/apply.html)(graphics: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>, wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>)<br>@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()<br>~~open~~ ~~fun~~ [~~apply~~](../-effect/apply.html)~~(~~~~graphic~~~~:~~ [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html)~~,~~ ~~node~~~~:~~ [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>~~,~~ ~~x~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~,~~ ~~y~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~)~~<br>open fun <[T](../-effect/apply.html), [P](../-effect/apply.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>?> [apply](../-effect/apply.html)(g: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html)>, env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>, wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>)<br>Applies the effect. |
| [drawFunction](draw-function.html) | [jvm]<br>open fun <[T](draw-function.html), [P](draw-function.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>?> [drawFunction](draw-function.html)(function: (out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)) -> out [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>, graphics: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>) |
| [drawLayers](../-abstract-draw-layers/draw-layers.html) | [jvm]<br>abstract fun <[T](../-abstract-draw-layers/draw-layers.html), [P](../-abstract-draw-layers/draw-layers.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>?> [drawLayers](../-abstract-draw-layers/draw-layers.html)(toDraw: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>, graphics: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>)<br>Effectively draw the layers.<br>[jvm]<br>open fun <[T](../-draw-layers-values/draw-layers.html), [P](../-draw-layers-values/draw-layers.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>?> [drawLayers](../-draw-layers-values/draw-layers.html)(toDraw: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>, graphics: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>) |
| [equals](../-effect/equals.html) | [jvm]<br>abstract fun [equals](../-effect/equals.html)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getAlpha](../-draw-bidimensional-gaussian-layers-gradient/index.html#-1609809598%2FFunctions%2F-134779887) | [jvm]<br>open fun [getAlpha](../-draw-bidimensional-gaussian-layers-gradient/index.html#-1609809598%2FFunctions%2F-134779887)(): RangedInteger<br>alpha channel |
| [getBlue](../-draw-bidimensional-gaussian-layers-gradient/index.html#1167250208%2FFunctions%2F-134779887) | [jvm]<br>open fun [getBlue](../-draw-bidimensional-gaussian-layers-gradient/index.html#1167250208%2FFunctions%2F-134779887)(): RangedInteger<br>blue channel |
| [getColorSummary](../-abstract-draw-layers/get-color-summary.html) | [jvm]<br>open fun [getColorSummary](../-abstract-draw-layers/get-color-summary.html)(): [Color](https://docs.oracle.com/javase/8/docs/api/java/awt/Color.html) |
| [getGreen](../-draw-bidimensional-gaussian-layers-gradient/index.html#-1357752515%2FFunctions%2F-134779887) | [jvm]<br>open fun [getGreen](../-draw-bidimensional-gaussian-layers-gradient/index.html#-1357752515%2FFunctions%2F-134779887)(): RangedInteger<br>green channel |
| [getMarkerNodeID](../-draw-bidimensional-gaussian-layers-gradient/index.html#470324422%2FFunctions%2F-134779887) | [jvm]<br>@[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()<br>open fun [getMarkerNodeID](../-draw-bidimensional-gaussian-layers-gradient/index.html#470324422%2FFunctions%2F-134779887)(): [Integer](https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html)<br>the marker node id |
| [getMaxLayerValue](../-draw-bidimensional-gaussian-layers-gradient/index.html#-137617604%2FFunctions%2F-134779887) | [jvm]<br>open fun [getMaxLayerValue](../-draw-bidimensional-gaussian-layers-gradient/index.html#-137617604%2FFunctions%2F-134779887)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>a string representation of the max layer value |
| [getMinLayerValue](../-draw-bidimensional-gaussian-layers-gradient/index.html#177375118%2FFunctions%2F-134779887) | [jvm]<br>open fun [getMinLayerValue](../-draw-bidimensional-gaussian-layers-gradient/index.html#177375118%2FFunctions%2F-134779887)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>a string representation of the min layer value |
| [getMolString](../-draw-bidimensional-gaussian-layers-gradient/index.html#676927493%2FFunctions%2F-134779887) | [jvm]<br>open fun [getMolString](../-draw-bidimensional-gaussian-layers-gradient/index.html#676927493%2FFunctions%2F-134779887)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>a string representing the current molecule |
| [getNumberOfIsolines](get-number-of-isolines.html) | [jvm]<br>open fun [getNumberOfIsolines](get-number-of-isolines.html)(): RangedInteger<br>the number of isolines |
| [getRed](../-draw-bidimensional-gaussian-layers-gradient/index.html#997430831%2FFunctions%2F-134779887) | [jvm]<br>open fun [getRed](../-draw-bidimensional-gaussian-layers-gradient/index.html#997430831%2FFunctions%2F-134779887)(): RangedInteger<br>red channel |
| [hashCode](../-effect/hash-code.html) | [jvm]<br>abstract fun [hashCode](../-effect/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isLayerFilter](../-abstract-draw-layers/is-layer-filter.html) | [jvm]<br>open fun [isLayerFilter](../-abstract-draw-layers/is-layer-filter.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>a boolean representing whether or not layer filter is on |
| [linspace](linspace.html) | [jvm]<br>open fun [linspace](linspace.html)(d1: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), d2: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), n: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)><br>generates n linearly-spaced points between d1 and d2. |
| [logspace](logspace.html) | [jvm]<br>open fun [logspace](logspace.html)(d1: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), d2: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), n: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), base: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)><br>generates n logarithmically-spaced points between d1 and d2 using the provided base. |
| [setAlpha](../-draw-bidimensional-gaussian-layers-gradient/index.html#-256941374%2FFunctions%2F-134779887) | [jvm]<br>open fun [setAlpha](../-draw-bidimensional-gaussian-layers-gradient/index.html#-256941374%2FFunctions%2F-134779887)(alpha: RangedInteger)<br>alpha channel |
| [setBlue](../-draw-bidimensional-gaussian-layers-gradient/index.html#-354420728%2FFunctions%2F-134779887) | [jvm]<br>open fun [setBlue](../-draw-bidimensional-gaussian-layers-gradient/index.html#-354420728%2FFunctions%2F-134779887)(blue: RangedInteger)<br>blue channel |
| [setGreen](../-draw-bidimensional-gaussian-layers-gradient/index.html#2124109629%2FFunctions%2F-134779887) | [jvm]<br>open fun [setGreen](../-draw-bidimensional-gaussian-layers-gradient/index.html#2124109629%2FFunctions%2F-134779887)(green: RangedInteger)<br>green channel |
| [setLayerFilter](../-draw-bidimensional-gaussian-layers-gradient/index.html#792349975%2FFunctions%2F-134779887) | [jvm]<br>open fun [setLayerFilter](../-draw-bidimensional-gaussian-layers-gradient/index.html#792349975%2FFunctions%2F-134779887)(layerFilter: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>a boolean representing whether or not layer filter must be on |
| [setMaxLayerValue](../-draw-bidimensional-gaussian-layers-gradient/index.html#702102851%2FFunctions%2F-134779887) | [jvm]<br>open fun [setMaxLayerValue](../-draw-bidimensional-gaussian-layers-gradient/index.html#702102851%2FFunctions%2F-134779887)(maxLayerValue: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>a string representation of the max layer value to set |
| [setMinLayerValue](../-draw-bidimensional-gaussian-layers-gradient/index.html#-919027307%2FFunctions%2F-134779887) | [jvm]<br>open fun [setMinLayerValue](../-draw-bidimensional-gaussian-layers-gradient/index.html#-919027307%2FFunctions%2F-134779887)(minLayerValue: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>a string representation of the min layer value to set |
| [setMolString](../-draw-bidimensional-gaussian-layers-gradient/index.html#-2103088628%2FFunctions%2F-134779887) | [jvm]<br>open fun [setMolString](../-draw-bidimensional-gaussian-layers-gradient/index.html#-2103088628%2FFunctions%2F-134779887)(molString: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>a string representing the molecule to use |
| [setNumberOfIsolines](set-number-of-isolines.html) | [jvm]<br>open fun [setNumberOfIsolines](set-number-of-isolines.html)(nOfIsolines: RangedInteger)<br>the number of isolines |
| [setRed](../-draw-bidimensional-gaussian-layers-gradient/index.html#1704630319%2FFunctions%2F-134779887) | [jvm]<br>open fun [setRed](../-draw-bidimensional-gaussian-layers-gradient/index.html#1704630319%2FFunctions%2F-134779887)(red: RangedInteger)<br>red channel |


## Properties


| Name | Summary |
|---|---|
| [distribution](distribution.html) | [jvm]<br>private open var [distribution](distribution.html): [DrawLayersIsolines.Distribution](-distribution/index.html) |
| [drawValues](draw-values.html) | [jvm]<br>private open var [drawValues](draw-values.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |


## Inheritors


| Name |
|---|
| [DrawBidimensionalGaussianLayersIsolines](../-draw-bidimensional-gaussian-layers-isolines/index.html) |

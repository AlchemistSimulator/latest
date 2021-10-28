---
title: DrawColoredDot
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.effects](../index.html)/[DrawColoredDot](index.html)



# DrawColoredDot



[jvm]\
open class [DrawColoredDot](index.html)<[P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>?> : [DrawDot](../-draw-dot/index.html)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)> 

Simple effect that draws a colored dot for each [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.html). 



 It's possible to set the size and the color of the dots.



## Parameters


jvm

| | |
|---|---|
| <P> | position type |



## Constructors


| | |
|---|---|
| [DrawColoredDot](-draw-colored-dot.html) | [jvm]<br>open fun [DrawColoredDot](-draw-colored-dot.html)()<br>Empty constructor. |
| [DrawColoredDot](-draw-colored-dot.html) | [jvm]<br>open fun [DrawColoredDot](-draw-colored-dot.html)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Default constructor. |


## Functions


| Name | Summary |
|---|---|
| [alphaProperty](alpha-property.html) | [jvm]<br>open fun [alphaProperty](alpha-property.html)(): DoubleProperty<br>The alpha channel of the color of the dots representing each [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.html) in the [it.unibo.alchemist.model.interfaces.Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html) specified when drawing. |
| [blueProperty](blue-property.html) | [jvm]<br>open fun [blueProperty](blue-property.html)(): IntegerProperty<br>The blue channel of the color of the dots representing each [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.html) in the [it.unibo.alchemist.model.interfaces.Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html) specified when drawing. |
| [computeDrawCommands](../-abstract-effect/compute-draw-commands.html) | [jvm]<br>open fun <[T](../-abstract-effect/compute-draw-commands.html)> [computeDrawCommands](../-abstract-effect/compute-draw-commands.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html), [P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>): [Queue](https://docs.oracle.com/javase/8/docs/api/java/util/Queue.html)<[DrawCommand](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>><br>abstract fun <[T](../-effect-f-x/compute-draw-commands.html)> [computeDrawCommands](../-effect-f-x/compute-draw-commands.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html), [P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>): [Queue](https://docs.oracle.com/javase/8/docs/api/java/util/Queue.html)<[DrawCommand](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>><br>Computes a queue of commands to Draw something. |
| [equals](../-abstract-effect/equals.html) | [jvm]<br>abstract fun [equals](../-abstract-effect/equals.html)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>open fun [equals](equals.html)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getColor](get-color.html) | [jvm]<br>fun [getColor](get-color.html)(): Color<br>Gets the color of the dots. |
| [getName](../-draw-dot/index.html#-1246522748%2FFunctions%2F-134779887) | [jvm]<br>fun [getName](../-draw-dot/index.html#-1246522748%2FFunctions%2F-134779887)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Gets the name of the effect. |
| [getSize](index.html#-1406090332%2FFunctions%2F-134779887) | [jvm]<br>open fun [getSize](index.html#-1406090332%2FFunctions%2F-134779887)(): [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)<br>Gets the value of the property {@code sizeProperty}. |
| [greenProperty](green-property.html) | [jvm]<br>open fun [greenProperty](green-property.html)(): IntegerProperty<br>The green channel of the color of the dots representing each [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.html) in the [it.unibo.alchemist.model.interfaces.Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html) specified when drawing. |
| [hashCode](hash-code.html) | [jvm]<br>open fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isVisible](../-abstract-effect/is-visible.html) | [jvm]<br>fun [isVisible](../-abstract-effect/is-visible.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Gets the visibility of the effect. |
| [redProperty](red-property.html) | [jvm]<br>open fun [redProperty](red-property.html)(): IntegerProperty<br>The red channel of the color of the dots representing each [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.html) in the [it.unibo.alchemist.model.interfaces.Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html) specified when drawing. |
| [setColor](set-color.html) | [jvm]<br>fun [setColor](set-color.html)(color: Color)<br>Sets the color of the dots. |
| [setName](../-draw-dot/index.html#718293747%2FFunctions%2F-134779887) | [jvm]<br>fun [setName](../-draw-dot/index.html#718293747%2FFunctions%2F-134779887)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>abstract fun [setName](../-effect-f-x/set-name.html)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Sets the name of the effect. |
| [setSize](index.html#-1629362093%2FFunctions%2F-134779887) | [jvm]<br>open fun [setSize](index.html#-1629362093%2FFunctions%2F-134779887)(size: [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html))<br>Sets the value of the property {@code sizeProperty}. |
| [setVisibility](../-draw-dot/index.html#-144014039%2FFunctions%2F-134779887) | [jvm]<br>fun [setVisibility](../-draw-dot/index.html#-144014039%2FFunctions%2F-134779887)(visibility: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>abstract fun [setVisibility](../-effect-f-x/set-visibility.html)(visibility: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Sets the visibility of the effect. |
| [sizeProperty](../-draw-dot/size-property.html) | [jvm]<br>open fun [sizeProperty](../-draw-dot/size-property.html)(): DoubleProperty<br>The size of the dots representing each [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.html) in the [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html) specified when drawing. |


## Properties


| Name | Summary |
|---|---|
| [alpha](alpha.html) | [jvm]<br>private open var [alpha](alpha.html): [RangedDoubleProperty](../../it.unibo.alchemist.boundary.gui.view.properties/-ranged-double-property/index.html) |
| [blue](blue.html) | [jvm]<br>private open var [blue](blue.html): [RangedIntegerProperty](../../it.unibo.alchemist.boundary.gui.view.properties/-ranged-integer-property/index.html) |
| [green](green.html) | [jvm]<br>private open var [green](green.html): [RangedIntegerProperty](../../it.unibo.alchemist.boundary.gui.view.properties/-ranged-integer-property/index.html) |
| [red](red.html) | [jvm]<br>private open var [red](red.html): [RangedIntegerProperty](../../it.unibo.alchemist.boundary.gui.view.properties/-ranged-integer-property/index.html) |


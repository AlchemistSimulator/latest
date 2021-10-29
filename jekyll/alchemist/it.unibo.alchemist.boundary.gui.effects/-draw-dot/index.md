---
title: DrawDot
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.effects](../index.html)/[DrawDot](index.html)



# DrawDot



[jvm]\
open class [DrawDot](index.html)<[P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>?> : [AbstractEffect](../-abstract-effect/index.html)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)> 

Simple effect that draws a black dot for each [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.html). 



 It's possible to set the size of the dots.



## Parameters


jvm

| | |
|---|---|
| <P> | the position type |



## Constructors


| | |
|---|---|
| [DrawDot](-draw-dot.html) | [jvm]<br>open fun [DrawDot](-draw-dot.html)()<br>Empty constructor. |
| [DrawDot](-draw-dot.html) | [jvm]<br>open fun [DrawDot](-draw-dot.html)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Default constructor. |


## Functions


| Name | Summary |
|---|---|
| [computeDrawCommands](../-abstract-effect/compute-draw-commands.html) | [jvm]<br>open fun <[T](../-abstract-effect/compute-draw-commands.html)> [computeDrawCommands](../-abstract-effect/compute-draw-commands.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html), [P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>): [Queue](https://docs.oracle.com/javase/8/docs/api/java/util/Queue.html)<[DrawCommand](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>><br>abstract fun <[T](../-effect-f-x/compute-draw-commands.html)> [computeDrawCommands](../-effect-f-x/compute-draw-commands.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html), [P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>): [Queue](https://docs.oracle.com/javase/8/docs/api/java/util/Queue.html)<[DrawCommand](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>><br>Computes a queue of commands to Draw something. |
| [equals](equals.html) | [jvm]<br>open fun [equals](equals.html)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getName](index.html#-1246522748%2FFunctions%2F-134779887) | [jvm]<br>fun [getName](index.html#-1246522748%2FFunctions%2F-134779887)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Gets the name of the effect. |
| [hashCode](hash-code.html) | [jvm]<br>open fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isVisible](../-abstract-effect/is-visible.html) | [jvm]<br>fun [isVisible](../-abstract-effect/is-visible.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Gets the visibility of the effect. |
| [setName](index.html#718293747%2FFunctions%2F-134779887) | [jvm]<br>fun [setName](index.html#718293747%2FFunctions%2F-134779887)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>abstract fun [setName](../-effect-f-x/set-name.html)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Sets the name of the effect. |
| [setVisibility](index.html#-144014039%2FFunctions%2F-134779887) | [jvm]<br>fun [setVisibility](index.html#-144014039%2FFunctions%2F-134779887)(visibility: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>abstract fun [setVisibility](../-effect-f-x/set-visibility.html)(visibility: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Sets the visibility of the effect. |
| [sizeProperty](size-property.html) | [jvm]<br>open fun [sizeProperty](size-property.html)(): DoubleProperty<br>The size of the dots representing each [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.html) in the [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html) specified when drawing. |


## Properties


| Name | Summary |
|---|---|
| [size](size.html) | [jvm]<br>private open var [size](size.html): [RangedDoubleProperty](../../it.unibo.alchemist.boundary.gui.view.properties/-ranged-double-property/index.html) |


## Inheritors


| Name |
|---|
| [DrawColoredDot](../-draw-colored-dot/index.html) |


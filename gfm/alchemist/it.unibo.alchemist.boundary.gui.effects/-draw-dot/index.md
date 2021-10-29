//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.effects](../index.md)/[DrawDot](index.md)

# DrawDot

[jvm]\
open class [DrawDot](index.md)<[P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)>?> : [AbstractEffect](../-abstract-effect/index.md)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)> 

Simple effect that draws a black dot for each [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.md). 

 It's possible to set the size of the dots.

## Parameters

jvm

| | |
|---|---|
| <P> | the position type |

## Constructors

| | |
|---|---|
| [DrawDot](-draw-dot.md) | [jvm]<br>open fun [DrawDot](-draw-dot.md)()<br>Empty constructor. |
| [DrawDot](-draw-dot.md) | [jvm]<br>open fun [DrawDot](-draw-dot.md)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Default constructor. |

## Functions

| Name | Summary |
|---|---|
| [computeDrawCommands](../-abstract-effect/compute-draw-commands.md) | [jvm]<br>open fun <[T](../-abstract-effect/compute-draw-commands.md)> [computeDrawCommands](../-abstract-effect/compute-draw-commands.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.boundary.gui.view.properties/-serializable-enum-property/index.md), [P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)>): [Queue](https://docs.oracle.com/javase/8/docs/api/java/util/Queue.html)<[DrawCommand](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.md)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)>><br>abstract fun <[T](../-effect-f-x/compute-draw-commands.md)> [computeDrawCommands](../-effect-f-x/compute-draw-commands.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.boundary.gui.view.properties/-serializable-enum-property/index.md), [P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)>): [Queue](https://docs.oracle.com/javase/8/docs/api/java/util/Queue.html)<[DrawCommand](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.md)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)>><br>Computes a queue of commands to Draw something. |
| [equals](equals.md) | [jvm]<br>open fun [equals](equals.md)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getName](index.md#-1246522748%2FFunctions%2F-267951372) | [jvm]<br>fun [getName](index.md#-1246522748%2FFunctions%2F-267951372)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Gets the name of the effect. |
| [hashCode](hash-code.md) | [jvm]<br>open fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isVisible](../-abstract-effect/is-visible.md) | [jvm]<br>fun [isVisible](../-abstract-effect/is-visible.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Gets the visibility of the effect. |
| [setName](index.md#718293747%2FFunctions%2F-267951372) | [jvm]<br>fun [setName](index.md#718293747%2FFunctions%2F-267951372)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>abstract fun [setName](../-effect-f-x/set-name.md)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Sets the name of the effect. |
| [setVisibility](index.md#-144014039%2FFunctions%2F-267951372) | [jvm]<br>fun [setVisibility](index.md#-144014039%2FFunctions%2F-267951372)(visibility: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>abstract fun [setVisibility](../-effect-f-x/set-visibility.md)(visibility: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Sets the visibility of the effect. |
| [sizeProperty](size-property.md) | [jvm]<br>open fun [sizeProperty](size-property.md)(): DoubleProperty<br>The size of the dots representing each [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.md) in the [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md) specified when drawing. |

## Properties

| Name | Summary |
|---|---|
| [size](size.md) | [jvm]<br>private open var [size](size.md): [RangedDoubleProperty](../../it.unibo.alchemist.boundary.gui.view.properties/-ranged-double-property/index.md) |

## Inheritors

| Name |
|---|
| [DrawColoredDot](../-draw-colored-dot/index.md) |

//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.effects](../index.md)/[DrawColoredDot](index.md)

# DrawColoredDot

[jvm]\
open class [DrawColoredDot](index.md)<[P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../../it.unibo.alchemist.boundary.monitor.generic/-numeric-label-monitor/index.md)>?> : [DrawDot](../-draw-dot/index.md)<[P](../../it.unibo.alchemist.boundary.monitor.generic/-numeric-label-monitor/index.md)> 

Simple effect that draws a colored dot for each [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.md). 

 It's possible to set the size and the color of the dots.

## Parameters

jvm

| | |
|---|---|
| <P> | position type |

## Constructors

| | |
|---|---|
| [DrawColoredDot](-draw-colored-dot.md) | [jvm]<br>open fun [DrawColoredDot](-draw-colored-dot.md)()<br>Empty constructor. |
| [DrawColoredDot](-draw-colored-dot.md) | [jvm]<br>open fun [DrawColoredDot](-draw-colored-dot.md)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Default constructor. |

## Functions

| Name | Summary |
|---|---|
| [alphaProperty](alpha-property.md) | [jvm]<br>open fun [alphaProperty](alpha-property.md)(): DoubleProperty<br>The alpha channel of the color of the dots representing each [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.md) in the [it.unibo.alchemist.model.interfaces.Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md) specified when drawing. |
| [blueProperty](blue-property.md) | [jvm]<br>open fun [blueProperty](blue-property.md)(): IntegerProperty<br>The blue channel of the color of the dots representing each [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.md) in the [it.unibo.alchemist.model.interfaces.Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md) specified when drawing. |
| [computeDrawCommands](../-abstract-effect/compute-draw-commands.md) | [jvm]<br>open fun <[T](../-abstract-effect/compute-draw-commands.md)> [computeDrawCommands](../-abstract-effect/compute-draw-commands.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.boundary.monitor.generic/-numeric-label-monitor/index.md), [P](../../it.unibo.alchemist.boundary.monitor.generic/-numeric-label-monitor/index.md)>): [Queue](https://docs.oracle.com/javase/8/docs/api/java/util/Queue.html)<[DrawCommand](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.md)<[P](../../it.unibo.alchemist.boundary.monitor.generic/-numeric-label-monitor/index.md)>><br>abstract fun <[T](../-effect-f-x/compute-draw-commands.md)> [computeDrawCommands](../-effect-f-x/compute-draw-commands.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.boundary.monitor.generic/-numeric-label-monitor/index.md), [P](../../it.unibo.alchemist.boundary.monitor.generic/-numeric-label-monitor/index.md)>): [Queue](https://docs.oracle.com/javase/8/docs/api/java/util/Queue.html)<[DrawCommand](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.md)<[P](../../it.unibo.alchemist.boundary.monitor.generic/-numeric-label-monitor/index.md)>><br>Computes a queue of commands to Draw something. |
| [equals](../-abstract-effect/equals.md) | [jvm]<br>abstract fun [equals](../-abstract-effect/equals.md)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>open fun [equals](equals.md)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getColor](get-color.md) | [jvm]<br>fun [getColor](get-color.md)(): Color<br>Gets the color of the dots. |
| [getName](../-draw-dot/index.md#-1246522748%2FFunctions%2F-267951372) | [jvm]<br>fun [getName](../-draw-dot/index.md#-1246522748%2FFunctions%2F-267951372)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Gets the name of the effect. |
| [getSize](index.md#-1406090332%2FFunctions%2F-267951372) | [jvm]<br>open fun [getSize](index.md#-1406090332%2FFunctions%2F-267951372)(): [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)<br>Gets the value of the property {@code sizeProperty}. |
| [greenProperty](green-property.md) | [jvm]<br>open fun [greenProperty](green-property.md)(): IntegerProperty<br>The green channel of the color of the dots representing each [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.md) in the [it.unibo.alchemist.model.interfaces.Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md) specified when drawing. |
| [hashCode](hash-code.md) | [jvm]<br>open fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isVisible](../-abstract-effect/is-visible.md) | [jvm]<br>fun [isVisible](../-abstract-effect/is-visible.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Gets the visibility of the effect. |
| [redProperty](red-property.md) | [jvm]<br>open fun [redProperty](red-property.md)(): IntegerProperty<br>The red channel of the color of the dots representing each [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.md) in the [it.unibo.alchemist.model.interfaces.Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md) specified when drawing. |
| [setColor](set-color.md) | [jvm]<br>fun [setColor](set-color.md)(color: Color)<br>Sets the color of the dots. |
| [setName](../-draw-dot/index.md#718293747%2FFunctions%2F-267951372) | [jvm]<br>fun [setName](../-draw-dot/index.md#718293747%2FFunctions%2F-267951372)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>abstract fun [setName](../-effect-f-x/set-name.md)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Sets the name of the effect. |
| [setSize](index.md#-1629362093%2FFunctions%2F-267951372) | [jvm]<br>open fun [setSize](index.md#-1629362093%2FFunctions%2F-267951372)(size: [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html))<br>Sets the value of the property {@code sizeProperty}. |
| [setVisibility](../-draw-dot/index.md#-144014039%2FFunctions%2F-267951372) | [jvm]<br>fun [setVisibility](../-draw-dot/index.md#-144014039%2FFunctions%2F-267951372)(visibility: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>abstract fun [setVisibility](../-effect-f-x/set-visibility.md)(visibility: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Sets the visibility of the effect. |
| [sizeProperty](../-draw-dot/size-property.md) | [jvm]<br>open fun [sizeProperty](../-draw-dot/size-property.md)(): DoubleProperty<br>The size of the dots representing each [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.md) in the [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md) specified when drawing. |

## Properties

| Name | Summary |
|---|---|
| [alpha](alpha.md) | [jvm]<br>private open var [alpha](alpha.md): [RangedDoubleProperty](../../it.unibo.alchemist.boundary.gui.view.properties/-ranged-double-property/index.md) |
| [blue](blue.md) | [jvm]<br>private open var [blue](blue.md): [RangedIntegerProperty](../../it.unibo.alchemist.boundary.gui.view.properties/-ranged-integer-property/index.md) |
| [green](green.md) | [jvm]<br>private open var [green](green.md): [RangedIntegerProperty](../../it.unibo.alchemist.boundary.gui.view.properties/-ranged-integer-property/index.md) |
| [red](red.md) | [jvm]<br>private open var [red](red.md): [RangedIntegerProperty](../../it.unibo.alchemist.boundary.gui.view.properties/-ranged-integer-property/index.md) |

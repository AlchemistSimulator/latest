//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.effects](../index.md)/[AbstractEffect](index.md)

# AbstractEffect

[jvm]\
abstract class [AbstractEffect](index.md)<[P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.md)>?> : [EffectFX](../-effect-f-x/index.md)<[P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.md)> 

It models an abstract implementation of the [effect](../-effect-f-x/index.md) interface, implementing default name and visibility properties. 

 The effect behavior can be implemented via [computeDrawCommands](compute-draw-commands.md) template method.

## Parameters

jvm

| | |
|---|---|
| <P> | the position type |

## Functions

| Name | Summary |
|---|---|
| [computeDrawCommands](compute-draw-commands.md) | [jvm]<br>open fun <[T](compute-draw-commands.md)> [computeDrawCommands](compute-draw-commands.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.boundary.gui.view.properties/-serializable-enum-property/index.md), [P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.md)>): [Queue](https://docs.oracle.com/javase/8/docs/api/java/util/Queue.html)<[DrawCommand](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.md)<[P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.md)>><br>Computes a queue of commands to Draw something. |
| [equals](equals.md) | [jvm]<br>abstract fun [equals](equals.md)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hashCode](hash-code.md) | [jvm]<br>abstract fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isVisible](is-visible.md) | [jvm]<br>fun [isVisible](is-visible.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Gets the visibility of the effect. |
| [setName](../-effect-f-x/set-name.md) | [jvm]<br>abstract fun [setName](../-effect-f-x/set-name.md)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Sets the name of the effect. |
| [setVisibility](../-effect-f-x/set-visibility.md) | [jvm]<br>abstract fun [setVisibility](../-effect-f-x/set-visibility.md)(visibility: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Sets the visibility of the effect. |

## Properties

| Name | Summary |
|---|---|
| [name](name.md) | [jvm]<br>private open var [name](name.md): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [visibility](visibility.md) | [jvm]<br>private open var [visibility](visibility.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

## Inheritors

| Name |
|---|
| [DrawLinks](../-draw-links/index.md) |
| [DrawDot](../-draw-dot/index.md) |

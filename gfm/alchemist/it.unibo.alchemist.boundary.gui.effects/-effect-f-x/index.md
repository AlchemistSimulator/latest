//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.effects](../index.md)/[EffectFX](index.md)

# EffectFX

[jvm]\
interface [EffectFX](index.md)<[P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.md)>?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Graphical visualization of something happening in the environment.

## Parameters

jvm

| | |
|---|---|
| <P> | the position type |

## Functions

| Name | Summary |
|---|---|
| [computeDrawCommands](compute-draw-commands.md) | [jvm]<br>abstract fun <[T](compute-draw-commands.md)> [computeDrawCommands](compute-draw-commands.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.md), [P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.md)>): [Queue](https://docs.oracle.com/javase/8/docs/api/java/util/Queue.html)<[DrawCommand](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.md)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.md)>><br>Computes a queue of commands to Draw something. |
| [getName](get-name.md) | [jvm]<br>abstract fun [getName](get-name.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Gets the name of the effect. |
| [isVisible](is-visible.md) | [jvm]<br>abstract fun [isVisible](is-visible.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Gets the visibility of the effect. |
| [setName](set-name.md) | [jvm]<br>abstract fun [setName](set-name.md)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Sets the name of the effect. |
| [setVisibility](set-visibility.md) | [jvm]<br>abstract fun [setVisibility](set-visibility.md)(visibility: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Sets the visibility of the effect. |

## Inheritors

| Name |
|---|
| [EffectGroup](../-effect-group/index.md) |
| [AbstractEffect](../-abstract-effect/index.md) |

---
title: EffectFX
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.effects](../index.html)/[EffectFX](index.html)



# EffectFX



[jvm]\
interface [EffectFX](index.html)<[P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.html)>?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Graphical visualization of something happening in the environment.



## Parameters


jvm

| | |
|---|---|
| <P> | the position type |



## Functions


| Name | Summary |
|---|---|
| [computeDrawCommands](compute-draw-commands.html) | [jvm]<br>abstract fun <[T](compute-draw-commands.html)> [computeDrawCommands](compute-draw-commands.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html), [P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.html)>): [Queue](https://docs.oracle.com/javase/8/docs/api/java/util/Queue.html)<[DrawCommand](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.html)>><br>Computes a queue of commands to Draw something. |
| [getName](get-name.html) | [jvm]<br>abstract fun [getName](get-name.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Gets the name of the effect. |
| [isVisible](is-visible.html) | [jvm]<br>abstract fun [isVisible](is-visible.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Gets the visibility of the effect. |
| [setName](set-name.html) | [jvm]<br>abstract fun [setName](set-name.html)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Sets the name of the effect. |
| [setVisibility](set-visibility.html) | [jvm]<br>abstract fun [setVisibility](set-visibility.html)(visibility: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Sets the visibility of the effect. |


## Inheritors


| Name |
|---|
| [EffectGroup](../-effect-group/index.html) |
| [AbstractEffect](../-abstract-effect/index.html) |


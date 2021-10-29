---
title: AbstractEffect
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.effects](../index.html)/[AbstractEffect](index.html)



# AbstractEffect



[jvm]\
abstract class [AbstractEffect](index.html)<[P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.html)>?> : [EffectFX](../-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.html)> 

It models an abstract implementation of the [effect](../-effect-f-x/index.html) interface, implementing default name and visibility properties. 



 The effect behavior can be implemented via [computeDrawCommands](compute-draw-commands.html) template method.



## Parameters


jvm

| | |
|---|---|
| <P> | the position type |



## Functions


| Name | Summary |
|---|---|
| [computeDrawCommands](compute-draw-commands.html) | [jvm]<br>open fun <[T](compute-draw-commands.html)> [computeDrawCommands](compute-draw-commands.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html), [P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.html)>): [Queue](https://docs.oracle.com/javase/8/docs/api/java/util/Queue.html)<[DrawCommand](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.html)>><br>Computes a queue of commands to Draw something. |
| [equals](equals.html) | [jvm]<br>abstract fun [equals](equals.html)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hashCode](hash-code.html) | [jvm]<br>abstract fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isVisible](is-visible.html) | [jvm]<br>fun [isVisible](is-visible.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Gets the visibility of the effect. |
| [setName](../-effect-f-x/set-name.html) | [jvm]<br>abstract fun [setName](../-effect-f-x/set-name.html)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Sets the name of the effect. |
| [setVisibility](../-effect-f-x/set-visibility.html) | [jvm]<br>abstract fun [setVisibility](../-effect-f-x/set-visibility.html)(visibility: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Sets the visibility of the effect. |


## Properties


| Name | Summary |
|---|---|
| [name](name.html) | [jvm]<br>private open var [name](name.html): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [visibility](visibility.html) | [jvm]<br>private open var [visibility](visibility.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |


## Inheritors


| Name |
|---|
| [DrawLinks](../-draw-links/index.html) |
| [DrawDot](../-draw-dot/index.html) |


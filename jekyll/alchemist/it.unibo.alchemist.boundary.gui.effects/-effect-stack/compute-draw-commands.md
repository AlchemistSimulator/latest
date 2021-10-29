---
title: computeDrawCommands
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.effects](../index.html)/[EffectStack](index.html)/[computeDrawCommands](compute-draw-commands.html)



# computeDrawCommands



[jvm]\
open fun <[T](compute-draw-commands.html)> [computeDrawCommands](compute-draw-commands.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<T, [P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-serializer/effect-from-file.html)>): [Queue](https://docs.oracle.com/javase/8/docs/api/java/util/Queue.html)<[DrawCommand](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-serializer/effect-from-file.html)>>



Computes a queue of commands to Draw something.



#### Return



the queue of commands that should be run to draw the effect



## Parameters


jvm

| | |
|---|---|
| environment | the environment to gather data from |
| <T> | the [it.unibo.alchemist.model.interfaces.Concentration](../../it.unibo.alchemist.model.interfaces/-concentration/index.html) type |





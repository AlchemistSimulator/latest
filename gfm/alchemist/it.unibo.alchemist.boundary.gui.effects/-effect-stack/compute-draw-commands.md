//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.effects](../index.md)/[EffectStack](index.md)/[computeDrawCommands](compute-draw-commands.md)

# computeDrawCommands

[jvm]\
open fun <[T](compute-draw-commands.md)> [computeDrawCommands](compute-draw-commands.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.boundary.gui.view.properties/-serializable-enum-property/index.md), [P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.md)>): [Queue](https://docs.oracle.com/javase/8/docs/api/java/util/Queue.html)<[DrawCommand](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.md)<[P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.md)>>

Computes a queue of commands to Draw something.

#### Return

the queue of commands that should be run to draw the effect

## Parameters

jvm

| | |
|---|---|
| environment | the environment to gather data from |
| <T> | the [it.unibo.alchemist.model.interfaces.Concentration](../../it.unibo.alchemist.model.interfaces/-concentration/index.md) type |

//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.effects](../index.md)/[EffectFX](index.md)/[computeDrawCommands](compute-draw-commands.md)

# computeDrawCommands

[jvm]\
abstract fun <[T](compute-draw-commands.md)> [computeDrawCommands](compute-draw-commands.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.md), [P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.md)>): [Queue](https://docs.oracle.com/javase/8/docs/api/java/util/Queue.html)<[DrawCommand](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.md)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.md)>>

Computes a queue of commands to Draw something.

#### Return

the queue of commands that should be run to draw the effect

## Parameters

jvm

| | |
|---|---|
| environment | the environment to gather data from |
| <T> | the [it.unibo.alchemist.model.interfaces.Concentration](../../it.unibo.alchemist.model.interfaces/-concentration/index.md) type |

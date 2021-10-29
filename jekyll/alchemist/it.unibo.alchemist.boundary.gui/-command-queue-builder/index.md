---
title: CommandQueueBuilder
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui](../index.html)/[CommandQueueBuilder](index.html)



# CommandQueueBuilder



[jvm]\
class [CommandQueueBuilder](index.html)<[P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-serializer/effect-from-file.html)>?>

Builder class that eases the building of a queue of [DrawCommand](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)s.



## Parameters


jvm

| | |
|---|---|
| <P> | the position type |



## Functions


| Name | Summary |
|---|---|
| [addCommand](add-command.html) | [jvm]<br>open fun [addCommand](add-command.html)(doOnJFXThread: [DrawCommand](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-serializer/effect-from-file.html)>): [CommandQueueBuilder](index.html)<br>Adds a {@code DrawCommand} to the queue to be executed on the JavaFX thread. |
| [buildCommandQueue](build-command-queue.html) | [jvm]<br>open fun [buildCommandQueue](build-command-queue.html)(): [Queue](https://docs.oracle.com/javase/8/docs/api/java/util/Queue.html)<[DrawCommand](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-serializer/effect-from-file.html)>><br>Builds the queue of commands. |
| [cleanQueue](clean-queue.html) | [jvm]<br>open fun [cleanQueue](clean-queue.html)(): [CommandQueueBuilder](index.html)<br>Clears the queue. |
| [wrapAndAdd](wrap-and-add.html) | [jvm]<br>open fun [wrapAndAdd](wrap-and-add.html)(supplier: [Supplier](https://docs.oracle.com/javase/8/docs/api/java/util/function/Supplier.html)<[Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)>, doOnJFXThread: [DrawCommand](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-serializer/effect-from-file.html)>): [CommandQueueBuilder](index.html)<br>Wraps a {@code DrawCommand} around to the queue to be executed on the JavaFX thread. |


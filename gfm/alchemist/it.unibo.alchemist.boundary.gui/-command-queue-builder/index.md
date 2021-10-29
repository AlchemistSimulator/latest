//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui](../index.md)/[CommandQueueBuilder](index.md)

# CommandQueueBuilder

[jvm]\
class [CommandQueueBuilder](index.md)<[P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>?>

Builder class that eases the building of a queue of [DrawCommand](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.md)s.

## Parameters

jvm

| | |
|---|---|
| <P> | the position type |

## Functions

| Name | Summary |
|---|---|
| [addCommand](add-command.md) | [jvm]<br>open fun [addCommand](add-command.md)(doOnJFXThread: [DrawCommand](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.md)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>): [CommandQueueBuilder](index.md)<br>Adds a {@code DrawCommand} to the queue to be executed on the JavaFX thread. |
| [buildCommandQueue](build-command-queue.md) | [jvm]<br>open fun [buildCommandQueue](build-command-queue.md)(): [Queue](https://docs.oracle.com/javase/8/docs/api/java/util/Queue.html)<[DrawCommand](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.md)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>><br>Builds the queue of commands. |
| [cleanQueue](clean-queue.md) | [jvm]<br>open fun [cleanQueue](clean-queue.md)(): [CommandQueueBuilder](index.md)<br>Clears the queue. |
| [wrapAndAdd](wrap-and-add.md) | [jvm]<br>open fun [wrapAndAdd](wrap-and-add.md)(supplier: [Supplier](https://docs.oracle.com/javase/8/docs/api/java/util/function/Supplier.html)<[Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)>, doOnJFXThread: [DrawCommand](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.md)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>): [CommandQueueBuilder](index.md)<br>Wraps a {@code DrawCommand} around to the queue to be executed on the JavaFX thread. |

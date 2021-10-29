//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui](../index.md)/[CommandQueueBuilder](index.md)/[wrapAndAdd](wrap-and-add.md)

# wrapAndAdd

[jvm]\
open fun [wrapAndAdd](wrap-and-add.md)(supplier: [Supplier](https://docs.oracle.com/javase/8/docs/api/java/util/function/Supplier.html)<[Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)>, doOnJFXThread: [DrawCommand](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.md)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>): [CommandQueueBuilder](index.md)

Wraps a {@code DrawCommand} around to the queue to be executed on the JavaFX thread.

#### Return

this builder

## Parameters

jvm

| | |
|---|---|
| doOnJFXThread | the action to do |
| supplier | the boolean supplier that will check if the command should be executed |

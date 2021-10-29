---
title: wrapAndAdd
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui](../index.html)/[CommandQueueBuilder](index.html)/[wrapAndAdd](wrap-and-add.html)



# wrapAndAdd



[jvm]\
open fun [wrapAndAdd](wrap-and-add.html)(supplier: [Supplier](https://docs.oracle.com/javase/8/docs/api/java/util/function/Supplier.html)<[Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)>, doOnJFXThread: [DrawCommand](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>): [CommandQueueBuilder](index.html)



Wraps a {@code DrawCommand} around to the queue to be executed on the JavaFX thread.



#### Return



this builder



## Parameters


jvm

| | |
|---|---|
| doOnJFXThread | the action to do |
| supplier | the boolean supplier that will check if the command should be executed |





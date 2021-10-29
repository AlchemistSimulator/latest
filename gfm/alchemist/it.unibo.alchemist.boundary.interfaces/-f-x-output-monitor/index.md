//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.interfaces](../index.md)/[FXOutputMonitor](index.md)

# FXOutputMonitor

[jvm]\
interface [FXOutputMonitor](index.md)<[T](index.md), [P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../-draw-command/index.md)>?> : [OutputMonitor](../-output-monitor/index.md)<[T](https://docs.oracle.com/javase/8/docs/api/java/util/function/BiConsumer.html), [P](../-draw-command/index.md)> 

{@code OutputMonitor} that handles the graphical part of the simulation in JavaFX.

## Parameters

jvm

| | |
|---|---|
| <T> | the [it.unibo.alchemist.model.interfaces.Concentration](../../it.unibo.alchemist.model.interfaces/-concentration/index.md) type |
| <P> | the position type |

## Types

| Name | Summary |
|---|---|
| [ViewStatus](-view-status/index.md) | [jvm]<br>enum [ViewStatus](-view-status/index.md)<br>The enum models the status of the view. |

## Functions

| Name | Summary |
|---|---|
| [addEffectGroup](add-effect-group.md) | [jvm]<br>abstract fun [addEffectGroup](add-effect-group.md)(effects: [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md)<[P](../-draw-command/index.md)>)<br>Add the [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md) in the collection to the [Effects](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.md) to draw. |
| [addEffects](add-effects.md) | [jvm]<br>abstract fun [addEffects](add-effects.md)(effects: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md)<[P](../-draw-command/index.md)>>)<br>Add all the [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md)s in the collection to the [Effects](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.md) to draw. |
| [asJavaFXNode](as-java-f-x-node.md) | [jvm]<br>abstract fun [asJavaFXNode](as-java-f-x-node.md)(): Node<br>Returns the JavaFX Node that is this monitor. |
| [finished](../-output-monitor/finished.md) | [jvm]<br>abstract fun [finished](../-output-monitor/finished.md)(p: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](https://docs.oracle.com/javase/8/docs/api/java/util/function/BiConsumer.html), [P](../-draw-command/index.md)>, p1: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), p2: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |
| [getEffects](get-effects.md) | [jvm]<br>abstract fun [getEffects](get-effects.md)(): [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md)<[P](../-draw-command/index.md)>><br>Getter method for the [Effects](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.md) to draw. |
| [getKeyboardListener](get-keyboard-listener.md) | [jvm]<br>abstract fun [getKeyboardListener](get-keyboard-listener.md)(): [KeyboardActionListener](../../it.unibo.alchemist.boundary.jfx.events.keyboard/-keyboard-action-listener/index.md)<br>Returns the keyboard listener associated with this monitor. |
| [getViewStatus](get-view-status.md) | [jvm]<br>abstract fun [getViewStatus](get-view-status.md)(): [FXOutputMonitor.ViewStatus](-view-status/index.md)<br>Getter method for the current view status. |
| [initialized](../-output-monitor/initialized.md) | [jvm]<br>abstract fun [initialized](../-output-monitor/initialized.md)(p: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](https://docs.oracle.com/javase/8/docs/api/java/util/function/BiConsumer.html), [P](../-draw-command/index.md)>) |
| [repaint](repaint.md) | [jvm]<br>abstract fun [repaint](repaint.md)()<br>Repaints this javafx.scene.canvas.Canvas' javafx.scene.canvas.GraphicsContext by drawing all the [Effect](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.md)s of each [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.md) of the specified [it.unibo.alchemist.model.interfaces.Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md). |
| [setEffects](set-effects.md) | [jvm]<br>abstract fun [setEffects](set-effects.md)(effects: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md)<[P](../-draw-command/index.md)>>)<br>Setter method for the effects to draw. |
| [setRealTime](set-real-time.md) | [jvm]<br>abstract fun [setRealTime](set-real-time.md)(realTime: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>If enabled, the monitor tries to synchronize the simulation time with the real time, slowing down the simulator if needed. |
| [setViewStatus](set-view-status.md) | [jvm]<br>abstract fun [setViewStatus](set-view-status.md)(viewStatus: [FXOutputMonitor.ViewStatus](-view-status/index.md))<br>Setter method for the current view status. |
| [stepDone](../-output-monitor/step-done.md) | [jvm]<br>abstract fun [stepDone](../-output-monitor/step-done.md)(p: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](https://docs.oracle.com/javase/8/docs/api/java/util/function/BiConsumer.html), [P](../-draw-command/index.md)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](https://docs.oracle.com/javase/8/docs/api/java/util/function/BiConsumer.html)>, p2: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), p3: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |

## Inheritors

| Name |
|---|
| [AbstractFXDisplay](../../it.unibo.alchemist.boundary.monitors/-abstract-f-x-display/index.md) |

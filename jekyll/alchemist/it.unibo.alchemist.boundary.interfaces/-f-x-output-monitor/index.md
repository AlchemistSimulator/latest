---
title: FXOutputMonitor
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.interfaces](../index.html)/[FXOutputMonitor](index.html)



# FXOutputMonitor



[jvm]\
interface [FXOutputMonitor](index.html)<[T](index.html), [P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../-draw-command/index.html)>?> : [OutputMonitor](../-output-monitor/index.html)<[T](../../it.unibo.alchemist.boundary.gui.view.properties/-property-type-adapter/index.html), [P](../-draw-command/index.html)> 

{@code OutputMonitor} that handles the graphical part of the simulation in JavaFX.



## Parameters


jvm

| | |
|---|---|
| <T> | the [it.unibo.alchemist.model.interfaces.Concentration](../../it.unibo.alchemist.model.interfaces/-concentration/index.html) type |
| <P> | the position type |



## Types


| Name | Summary |
|---|---|
| [ViewStatus](-view-status/index.html) | [jvm]<br>enum [ViewStatus](-view-status/index.html)<br>The enum models the status of the view. |


## Functions


| Name | Summary |
|---|---|
| [addEffectGroup](add-effect-group.html) | [jvm]<br>abstract fun [addEffectGroup](add-effect-group.html)(effects: [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html)<[P](../-draw-command/index.html)>)<br>Add the [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html) in the collection to the [Effects](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.html) to draw. |
| [addEffects](add-effects.html) | [jvm]<br>abstract fun [addEffects](add-effects.html)(effects: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html)<[P](../-draw-command/index.html)>>)<br>Add all the [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html)s in the collection to the [Effects](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.html) to draw. |
| [asJavaFXNode](as-java-f-x-node.html) | [jvm]<br>abstract fun [asJavaFXNode](as-java-f-x-node.html)(): Node<br>Returns the JavaFX Node that is this monitor. |
| [finished](../-output-monitor/finished.html) | [jvm]<br>abstract fun [finished](../-output-monitor/finished.html)(p: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.boundary.gui.view.properties/-property-type-adapter/index.html), [P](../-draw-command/index.html)>, p1: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), p2: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |
| [getEffects](get-effects.html) | [jvm]<br>abstract fun [getEffects](get-effects.html)(): [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html)<[P](../-draw-command/index.html)>><br>Getter method for the [Effects](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.html) to draw. |
| [getKeyboardListener](get-keyboard-listener.html) | [jvm]<br>abstract fun [getKeyboardListener](get-keyboard-listener.html)(): [KeyboardActionListener](../../it.unibo.alchemist.boundary.jfx.events.keyboard/-keyboard-action-listener/index.html)<br>Returns the keyboard listener associated with this monitor. |
| [getViewStatus](get-view-status.html) | [jvm]<br>abstract fun [getViewStatus](get-view-status.html)(): [FXOutputMonitor.ViewStatus](-view-status/index.html)<br>Getter method for the current view status. |
| [initialized](../-output-monitor/initialized.html) | [jvm]<br>abstract fun [initialized](../-output-monitor/initialized.html)(p: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.boundary.gui.view.properties/-property-type-adapter/index.html), [P](../-draw-command/index.html)>) |
| [repaint](repaint.html) | [jvm]<br>abstract fun [repaint](repaint.html)()<br>Repaints this javafx.scene.canvas.Canvas' javafx.scene.canvas.GraphicsContext by drawing all the [Effect](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.html)s of each [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.html) of the specified [it.unibo.alchemist.model.interfaces.Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html). |
| [setEffects](set-effects.html) | [jvm]<br>abstract fun [setEffects](set-effects.html)(effects: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html)<[P](../-draw-command/index.html)>>)<br>Setter method for the effects to draw. |
| [setRealTime](set-real-time.html) | [jvm]<br>abstract fun [setRealTime](set-real-time.html)(realTime: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>If enabled, the monitor tries to synchronize the simulation time with the real time, slowing down the simulator if needed. |
| [setViewStatus](set-view-status.html) | [jvm]<br>abstract fun [setViewStatus](set-view-status.html)(viewStatus: [FXOutputMonitor.ViewStatus](-view-status/index.html))<br>Setter method for the current view status. |
| [stepDone](../-output-monitor/step-done.html) | [jvm]<br>abstract fun [stepDone](../-output-monitor/step-done.html)(p: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.boundary.gui.view.properties/-property-type-adapter/index.html), [P](../-draw-command/index.html)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.boundary.gui.view.properties/-property-type-adapter/index.html)>, p2: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), p3: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |


## Inheritors


| Name |
|---|
| [AbstractFXDisplay](../../it.unibo.alchemist.boundary.monitors/-abstract-f-x-display/index.html) |


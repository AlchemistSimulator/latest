---
title: InteractionManager
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.interactions](../index.html)/[InteractionManager](index.html)



# InteractionManager



[jvm]\
interface [InteractionManager](index.html)<[T](index.html), [P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](index.html)>>

An interaction manager that controls the input/output on the environment done through the GUI.



## Functions


| Name | Summary |
|---|---|
| [onMonitorRepaint](on-monitor-repaint.html) | [jvm]<br>abstract fun [onMonitorRepaint](on-monitor-repaint.html)()<br>To be called whenever the monitor paints its effects. |
| [repaint](repaint.html) | [jvm]<br>abstract fun [repaint](repaint.html)()<br>Clears and then paints every currently active feedback. |
| [setWormhole](set-wormhole.html) | [jvm]<br>abstract fun [setWormhole](set-wormhole.html)(wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](index.html)>)<br>Sets the wormhole. |
| [setZoomManager](set-zoom-manager.html) | [jvm]<br>abstract fun [setZoomManager](set-zoom-manager.html)(zoomManager: [ZoomManager](../../it.unibo.alchemist.boundary.wormhole.interfaces/-zoom-manager/index.html))<br>Sets the zoom manager. |


## Properties


| Name | Summary |
|---|---|
| [canvases](canvases.html) | [jvm]<br>abstract val [canvases](canvases.html): Group<br>The canvases used for input/output. |
| [environment](environment.html) | [jvm]<br>abstract var [environment](environment.html): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](index.html)><br>The current environment. |
| [keyboardListener](keyboard-listener.html) | [jvm]<br>abstract val [keyboardListener](keyboard-listener.html): [KeyboardActionListener](../../it.unibo.alchemist.boundary.jfx.events.keyboard/-keyboard-action-listener/index.html)<br>The keyboard listener. |
| [nodes](nodes.html) | [jvm]<br>abstract var [nodes](nodes.html): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, [P](index.html)><br>The nodes in the environment. |


## Inheritors


| Name |
|---|
| [BaseInteractionManager](../-base-interaction-manager/index.html) |


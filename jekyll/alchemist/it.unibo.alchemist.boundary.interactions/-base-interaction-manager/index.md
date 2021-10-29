---
title: BaseInteractionManager
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.interactions](../index.html)/[BaseInteractionManager](index.html)



# BaseInteractionManager



[jvm]\
class [BaseInteractionManager](index.html)<[T](index.html), [P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](index.html)>>(**monitor**: [AbstractFXDisplay](../../it.unibo.alchemist.boundary.monitors/-abstract-f-x-display/index.html)<[T](index.html), [P](index.html)>) : [InteractionManager](../-interaction-manager/index.html)<[T](index.html), [P](index.html)> 

An interaction manager that implements pan, select, move, delete and zoom.



## Parameters


jvm

| | |
|---|---|
| monitor | the monitor. |



## Constructors


| | |
|---|---|
| [BaseInteractionManager](-base-interaction-manager.html) | [jvm]<br>fun <[T](index.html), [P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](index.html)>> [BaseInteractionManager](-base-interaction-manager.html)(monitor: [AbstractFXDisplay](../../it.unibo.alchemist.boundary.monitors/-abstract-f-x-display/index.html)<[T](index.html), [P](index.html)>)<br>the monitor. |


## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [onMonitorRepaint](on-monitor-repaint.html) | [jvm]<br>open override fun [onMonitorRepaint](on-monitor-repaint.html)()<br>To be called whenever the monitor paints its effects. |
| [repaint](repaint.html) | [jvm]<br>open override fun [repaint](repaint.html)()<br>Clears and then paints every currently active feedback. |
| [setWormhole](set-wormhole.html) | [jvm]<br>open override fun [setWormhole](set-wormhole.html)(wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](index.html)>)<br>Sets the wormhole. |
| [setZoomManager](set-zoom-manager.html) | [jvm]<br>open override fun [setZoomManager](set-zoom-manager.html)(zoomManager: [ZoomManager](../../it.unibo.alchemist.boundary.wormhole.interfaces/-zoom-manager/index.html))<br>Sets the zoom manager. |


## Properties


| Name | Summary |
|---|---|
| [canvases](canvases.html) | [jvm]<br>open override val [canvases](canvases.html): Group<br>The canvases used for input/output. |
| [environment](environment.html) | [jvm]<br>open lateinit override var [environment](environment.html): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](index.html)><br>The current environment. |
| [keyboardListener](keyboard-listener.html) | [jvm]<br>open override val [keyboardListener](keyboard-listener.html): [KeyboardActionListener](../../it.unibo.alchemist.boundary.jfx.events.keyboard/-keyboard-action-listener/index.html)<br>The keyboard listener. |
| [nodes](nodes.html) | [jvm]<br>open override var [nodes](nodes.html): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, [P](index.html)><br>The nodes in the environment. |


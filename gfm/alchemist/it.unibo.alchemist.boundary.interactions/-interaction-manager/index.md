//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.interactions](../index.md)/[InteractionManager](index.md)

# InteractionManager

[jvm]\
interface [InteractionManager](index.md)<[T](index.md), [P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](index.md)>>

An interaction manager that controls the input/output on the environment done through the GUI.

## Functions

| Name | Summary |
|---|---|
| [onMonitorRepaint](on-monitor-repaint.md) | [jvm]<br>abstract fun [onMonitorRepaint](on-monitor-repaint.md)()<br>To be called whenever the monitor paints its effects. |
| [repaint](repaint.md) | [jvm]<br>abstract fun [repaint](repaint.md)()<br>Clears and then paints every currently active feedback. |
| [setWormhole](set-wormhole.md) | [jvm]<br>abstract fun [setWormhole](set-wormhole.md)(wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)<[P](index.md)>)<br>Sets the wormhole. |
| [setZoomManager](set-zoom-manager.md) | [jvm]<br>abstract fun [setZoomManager](set-zoom-manager.md)(zoomManager: [ZoomManager](../../it.unibo.alchemist.boundary.wormhole.interfaces/-zoom-manager/index.md))<br>Sets the zoom manager. |

## Properties

| Name | Summary |
|---|---|
| [canvases](canvases.md) | [jvm]<br>abstract val [canvases](canvases.md): Group<br>The canvases used for input/output. |
| [environment](environment.md) | [jvm]<br>abstract var [environment](environment.md): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [P](index.md)><br>The current environment. |
| [keyboardListener](keyboard-listener.md) | [jvm]<br>abstract val [keyboardListener](keyboard-listener.md): [KeyboardActionListener](../../it.unibo.alchemist.boundary.jfx.events.keyboard/-keyboard-action-listener/index.md)<br>The keyboard listener. |
| [nodes](nodes.md) | [jvm]<br>abstract var [nodes](nodes.md): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, [P](index.md)><br>The nodes in the environment. |

## Inheritors

| Name |
|---|
| [BaseInteractionManager](../-base-interaction-manager/index.md) |

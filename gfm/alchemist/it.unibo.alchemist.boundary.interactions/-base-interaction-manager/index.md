//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.interactions](../index.md)/[BaseInteractionManager](index.md)

# BaseInteractionManager

[jvm]\
class [BaseInteractionManager](index.md)<[T](index.md), [P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](index.md)>>(**monitor**: [AbstractFXDisplay](../../it.unibo.alchemist.boundary.monitors/-abstract-f-x-display/index.md)<[T](index.md), [P](index.md)>) : [InteractionManager](../-interaction-manager/index.md)<[T](index.md), [P](index.md)> 

An interaction manager that implements pan, select, move, delete and zoom.

## Parameters

jvm

| | |
|---|---|
| monitor | the monitor. |

## Constructors

| | |
|---|---|
| [BaseInteractionManager](-base-interaction-manager.md) | [jvm]<br>fun <[T](index.md), [P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](index.md)>> [BaseInteractionManager](-base-interaction-manager.md)(monitor: [AbstractFXDisplay](../../it.unibo.alchemist.boundary.monitors/-abstract-f-x-display/index.md)<[T](index.md), [P](index.md)>)<br>the monitor. |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [jvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [onMonitorRepaint](on-monitor-repaint.md) | [jvm]<br>open override fun [onMonitorRepaint](on-monitor-repaint.md)()<br>To be called whenever the monitor paints its effects. |
| [repaint](repaint.md) | [jvm]<br>open override fun [repaint](repaint.md)()<br>Clears and then paints every currently active feedback. |
| [setWormhole](set-wormhole.md) | [jvm]<br>open override fun [setWormhole](set-wormhole.md)(wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)<[P](index.md)>)<br>Sets the wormhole. |
| [setZoomManager](set-zoom-manager.md) | [jvm]<br>open override fun [setZoomManager](set-zoom-manager.md)(zoomManager: [ZoomManager](../../it.unibo.alchemist.boundary.wormhole.interfaces/-zoom-manager/index.md))<br>Sets the zoom manager. |

## Properties

| Name | Summary |
|---|---|
| [canvases](canvases.md) | [jvm]<br>open override val [canvases](canvases.md): Group<br>The canvases used for input/output. |
| [environment](environment.md) | [jvm]<br>open lateinit override var [environment](environment.md): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [P](index.md)><br>The current environment. |
| [keyboardListener](keyboard-listener.md) | [jvm]<br>open override val [keyboardListener](keyboard-listener.md): [KeyboardActionListener](../../it.unibo.alchemist.boundary.jfx.events.keyboard/-keyboard-action-listener/index.md)<br>The keyboard listener. |
| [nodes](nodes.md) | [jvm]<br>open override var [nodes](nodes.md): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, [P](index.md)><br>The nodes in the environment. |

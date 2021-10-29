//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.interfaces](../index.md)/[Graphical2DOutputMonitor](index.md)

# Graphical2DOutputMonitor

[jvm]\
@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()

~~interface~~ [~~Graphical2DOutputMonitor~~](index.md)~~<~~[T](index.md)~~,~~ [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<out [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.md)>?~~>~~ ~~:~~ [~~GraphicalOutputMonitor~~](../-graphical-output-monitor/index.md)~~<~~[~~T~~](../../it.unibo.alchemist.boundary.gui.effects/-draw-layers-gradient/draw-function.md)~~,~~ [~~P~~](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.md)~~>~~ 

An output monitor that supports zooming on bidimensional environments.

## Parameters

jvm

| | |
|---|---|
| <P> | position type |
| <T> | concentration type |

## Functions

| Name | Summary |
|---|---|
| [finished](../-output-monitor/finished.md) | [jvm]<br>abstract fun [finished](../-output-monitor/finished.md)(p: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.boundary.gui.effects/-draw-layers-gradient/draw-function.md), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.md)>, p1: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), p2: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |
| [getStep](../-graphical-output-monitor/get-step.md) | [jvm]<br>abstract fun [getStep](../-graphical-output-monitor/get-step.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>how many simulation steps this monitor updates the graphics |
| [initialized](../-output-monitor/initialized.md) | [jvm]<br>abstract fun [initialized](../-output-monitor/initialized.md)(p: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.boundary.gui.effects/-draw-layers-gradient/draw-function.md), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.md)>) |
| [isRealTime](../-graphical-output-monitor/is-real-time.md) | [jvm]<br>abstract fun [isRealTime](../-graphical-output-monitor/is-real-time.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if this monitor is trying to draw in realtime |
| [repaint](../-graphical-output-monitor/repaint.md) | [jvm]<br>abstract fun [repaint](../-graphical-output-monitor/repaint.md)()<br>Repaints the GUI. |
| [setDrawLinks](../-graphical-output-monitor/set-draw-links.md) | [jvm]<br>abstract fun [setDrawLinks](../-graphical-output-monitor/set-draw-links.md)(b: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>if true, this monitor draws the links between nodes |
| [setEffectStack](../-graphical-output-monitor/set-effect-stack.md) | [jvm]<br>abstract fun [setEffectStack](../-graphical-output-monitor/set-effect-stack.md)(l: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Effect](../../it.unibo.alchemist.boundary.gui.effects/-effect/index.md)>)<br>the Effect stack to use |
| [setMarkCloserNode](../-graphical-output-monitor/set-mark-closer-node.md) | [jvm]<br>abstract fun [setMarkCloserNode](../-graphical-output-monitor/set-mark-closer-node.md)(mark: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>If set, the node closer to the mouse will be put in evidence. |
| [setRealTime](../-graphical-output-monitor/set-real-time.md) | [jvm]<br>abstract fun [setRealTime](../-graphical-output-monitor/set-real-time.md)(rt: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>If enabled, the monitor tries to synchronize the simulation time with the real time, slowing down the simulator if needed. |
| [setStep](../-graphical-output-monitor/set-step.md) | [jvm]<br>abstract fun [setStep](../-graphical-output-monitor/set-step.md)(step: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>How many steps should be computed by the engine for the display to update the graphics |
| [stepDone](../-output-monitor/step-done.md) | [jvm]<br>abstract fun [stepDone](../-output-monitor/step-done.md)(p: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.boundary.gui.effects/-draw-layers-gradient/draw-function.md), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.md)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.boundary.gui.effects/-draw-layers-gradient/draw-function.md)>, p2: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), p3: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |
| [zoomTo](zoom-to.md) | [jvm]<br>abstract fun [zoomTo](zoom-to.md)(center: [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.md), zoomLevel: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>the point where to zoom |

## Inheritors

| Name |
|---|
| [Generic2DDisplay](../../it.unibo.alchemist.boundary.monitors/-generic2-d-display/index.md) |

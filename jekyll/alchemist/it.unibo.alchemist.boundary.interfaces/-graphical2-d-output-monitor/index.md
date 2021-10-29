---
title: Graphical2DOutputMonitor
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.interfaces](../index.html)/[Graphical2DOutputMonitor](index.html)



# Graphical2DOutputMonitor



[jvm]\
@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()



~~interface~~ [~~Graphical2DOutputMonitor~~](index.html)~~<~~[T](index.html)~~,~~ [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>?~~>~~ ~~:~~ [~~GraphicalOutputMonitor~~](../-graphical-output-monitor/index.html)~~<~~[~~T~~](index.html)~~,~~ [~~P~~](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)~~>~~ 

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
| [finished](../-output-monitor/finished.html) | [jvm]<br>abstract fun [finished](../-output-monitor/finished.html)(p: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>, p1: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), p2: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |
| [getStep](../-graphical-output-monitor/get-step.html) | [jvm]<br>abstract fun [getStep](../-graphical-output-monitor/get-step.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>how many simulation steps this monitor updates the graphics |
| [initialized](../-output-monitor/initialized.html) | [jvm]<br>abstract fun [initialized](../-output-monitor/initialized.html)(p: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>) |
| [isRealTime](../-graphical-output-monitor/is-real-time.html) | [jvm]<br>abstract fun [isRealTime](../-graphical-output-monitor/is-real-time.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if this monitor is trying to draw in realtime |
| [repaint](../-graphical-output-monitor/repaint.html) | [jvm]<br>abstract fun [repaint](../-graphical-output-monitor/repaint.html)()<br>Repaints the GUI. |
| [setDrawLinks](../-graphical-output-monitor/set-draw-links.html) | [jvm]<br>abstract fun [setDrawLinks](../-graphical-output-monitor/set-draw-links.html)(b: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>if true, this monitor draws the links between nodes |
| [setEffectStack](../-graphical-output-monitor/set-effect-stack.html) | [jvm]<br>abstract fun [setEffectStack](../-graphical-output-monitor/set-effect-stack.html)(l: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Effect](../../it.unibo.alchemist.boundary.gui.effects/-effect/index.html)>)<br>the Effect stack to use |
| [setMarkCloserNode](../-graphical-output-monitor/set-mark-closer-node.html) | [jvm]<br>abstract fun [setMarkCloserNode](../-graphical-output-monitor/set-mark-closer-node.html)(mark: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>If set, the node closer to the mouse will be put in evidence. |
| [setRealTime](../-graphical-output-monitor/set-real-time.html) | [jvm]<br>abstract fun [setRealTime](../-graphical-output-monitor/set-real-time.html)(rt: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>If enabled, the monitor tries to synchronize the simulation time with the real time, slowing down the simulator if needed. |
| [setStep](../-graphical-output-monitor/set-step.html) | [jvm]<br>abstract fun [setStep](../-graphical-output-monitor/set-step.html)(step: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>How many steps should be computed by the engine for the display to update the graphics |
| [stepDone](../-output-monitor/step-done.html) | [jvm]<br>abstract fun [stepDone](../-output-monitor/step-done.html)(p: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>, p2: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), p3: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |
| [zoomTo](zoom-to.html) | [jvm]<br>abstract fun [zoomTo](zoom-to.html)(center: [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html), zoomLevel: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>the point where to zoom |


## Inheritors


| Name |
|---|
| [Generic2DDisplay](../../it.unibo.alchemist.boundary.monitors/-generic2-d-display/index.html) |


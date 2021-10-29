---
title: GraphicalOutputMonitor
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.interfaces](../index.html)/[GraphicalOutputMonitor](index.html)



# GraphicalOutputMonitor



[jvm]\
@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()



~~interface~~ [~~GraphicalOutputMonitor~~](index.html)~~<~~[T](index.html)~~,~~ [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>?~~>~~ ~~:~~ [~~OutputMonitor~~](../-output-monitor/index.html)~~<~~[~~T~~](../-graphical2-d-output-monitor/index.html)~~,~~ [~~P~~](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)~~>~~ 

{@code OutputMonitor} that handles the graphical part of the simulation.



## Parameters


jvm

| | |
|---|---|
| <P> | position type |
| <T> | concentration type |



## Functions


| Name | Summary |
|---|---|
| [finished](../-output-monitor/finished.html) | [jvm]<br>abstract fun [finished](../-output-monitor/finished.html)(p: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../-graphical2-d-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>, p1: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), p2: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |
| [getStep](get-step.html) | [jvm]<br>abstract fun [getStep](get-step.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>how many simulation steps this monitor updates the graphics |
| [initialized](../-output-monitor/initialized.html) | [jvm]<br>abstract fun [initialized](../-output-monitor/initialized.html)(p: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../-graphical2-d-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>) |
| [isRealTime](is-real-time.html) | [jvm]<br>abstract fun [isRealTime](is-real-time.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if this monitor is trying to draw in realtime |
| [repaint](repaint.html) | [jvm]<br>abstract fun [repaint](repaint.html)()<br>Repaints the GUI. |
| [setDrawLinks](set-draw-links.html) | [jvm]<br>abstract fun [setDrawLinks](set-draw-links.html)(b: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>if true, this monitor draws the links between nodes |
| [setEffectStack](set-effect-stack.html) | [jvm]<br>abstract fun [setEffectStack](set-effect-stack.html)(l: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Effect](../../it.unibo.alchemist.boundary.gui.effects/-effect/index.html)>)<br>the Effect stack to use |
| [setMarkCloserNode](set-mark-closer-node.html) | [jvm]<br>abstract fun [setMarkCloserNode](set-mark-closer-node.html)(mark: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>If set, the node closer to the mouse will be put in evidence. |
| [setRealTime](set-real-time.html) | [jvm]<br>abstract fun [setRealTime](set-real-time.html)(rt: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>If enabled, the monitor tries to synchronize the simulation time with the real time, slowing down the simulator if needed. |
| [setStep](set-step.html) | [jvm]<br>abstract fun [setStep](set-step.html)(step: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>How many steps should be computed by the engine for the display to update the graphics |
| [stepDone](../-output-monitor/step-done.html) | [jvm]<br>abstract fun [stepDone](../-output-monitor/step-done.html)(p: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../-graphical2-d-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../-graphical2-d-output-monitor/index.html)>, p2: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), p3: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |


## Inheritors


| Name |
|---|
| [Graphical2DOutputMonitor](../-graphical2-d-output-monitor/index.html) |


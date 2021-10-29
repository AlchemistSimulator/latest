---
title: it.unibo.alchemist.boundary.interfaces
---
//[alchemist](../../index.html)/[it.unibo.alchemist.boundary.interfaces](index.html)



# Package it.unibo.alchemist.boundary.interfaces



[jvm]\
This package contains the interfaces to implement in order to create a common input-output.



## Types


| Name | Summary |
|---|---|
| [DrawCommand](-draw-command/index.html) | [jvm]<br>@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()<br>interface [DrawCommand](-draw-command/index.html)<[P](-draw-command/index.html) : [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>?> : [BiConsumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/BiConsumer.html)<GraphicsContext, [Wormhole2D](../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>> <br>Functional interface that models a command for JavaFX thread to draw something on a javafx.scene.canvas.Canvas. |
| [FXOutputMonitor](-f-x-output-monitor/index.html) | [jvm]<br>interface [FXOutputMonitor](-f-x-output-monitor/index.html)<[T](-f-x-output-monitor/index.html), [P](-f-x-output-monitor/index.html) : [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>?> : [OutputMonitor](-output-monitor/index.html)<[T](../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html), [P](../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)> <br>{@code OutputMonitor} that handles the graphical part of the simulation in JavaFX. |
| [Graphical2DOutputMonitor](-graphical2-d-output-monitor/index.html) | [jvm]<br>@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()<br>~~interface~~ [~~Graphical2DOutputMonitor~~](-graphical2-d-output-monitor/index.html)~~<~~[T](-graphical2-d-output-monitor/index.html)~~,~~ [P](-graphical2-d-output-monitor/index.html) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](-graphical2-d-output-monitor/index.html)>?~~>~~ ~~:~~ [~~GraphicalOutputMonitor~~](-graphical-output-monitor/index.html)~~<~~[~~T~~](-graphical2-d-output-monitor/index.html)~~,~~ [~~P~~](-graphical2-d-output-monitor/index.html)~~>~~ <br>An output monitor that supports zooming on bidimensional environments. |
| [GraphicalOutputMonitor](-graphical-output-monitor/index.html) | [jvm]<br>@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()<br>~~interface~~ [~~GraphicalOutputMonitor~~](-graphical-output-monitor/index.html)~~<~~[T](-graphical-output-monitor/index.html)~~,~~ [P](-graphical-output-monitor/index.html) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](-graphical2-d-output-monitor/index.html)>?~~>~~ ~~:~~ [~~OutputMonitor~~](-output-monitor/index.html)~~<~~[~~T~~](-graphical2-d-output-monitor/index.html)~~,~~ [~~P~~](-graphical2-d-output-monitor/index.html)~~>~~ <br>{@code OutputMonitor} that handles the graphical part of the simulation. |
| [OutputMonitor](-output-monitor/index.html) | [jvm]<br>interface [OutputMonitor](-output-monitor/index.html)<[T](-output-monitor/index.html), [P](-output-monitor/index.html) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](-output-monitor/index.html)>?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>An interface for the visualization of the simulation. |


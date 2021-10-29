//[alchemist](../../index.md)/[it.unibo.alchemist.boundary.monitor](index.md)

# Package it.unibo.alchemist.boundary.monitor

[jvm]\
This package contains generic monitors for various Environments.

## Types

| Name | Summary |
|---|---|
| [FXStepMonitor](-f-x-step-monitor/index.md) | [jvm]<br>open class [FXStepMonitor](-f-x-step-monitor/index.md)<[T](-f-x-step-monitor/index.md), [P](-f-x-step-monitor/index.md) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.md)<out [P](../it.unibo.alchemist.boundary.interfaces/-draw-command/index.md)>?> : [NumericLabelMonitor](../it.unibo.alchemist.boundary.monitor.generic/-numeric-label-monitor/index.md)<[Long](https://docs.oracle.com/javase/8/docs/api/java/lang/Long.html), [T](https://docs.oracle.com/javase/8/docs/api/java/util/function/BiConsumer.html), [P](../it.unibo.alchemist.boundary.interfaces/-draw-command/index.md)> <br>{@code OutputMonitor} that monitors the current [steps](../it.unibo.alchemist.core.interfaces/-simulation/get-step.md) of the {@code Simulation}. |
| [FXTimeMonitor](-f-x-time-monitor/index.md) | [jvm]<br>open class [FXTimeMonitor](-f-x-time-monitor/index.md)<[T](-f-x-time-monitor/index.md), [P](-f-x-time-monitor/index.md) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.md)<out [P](../it.unibo.alchemist.boundary.interfaces/-draw-command/index.md)>?> : [NumericLabelMonitor](../it.unibo.alchemist.boundary.monitor.generic/-numeric-label-monitor/index.md)<[Time](../it.unibo.alchemist.model.interfaces/-time/index.md), [T](https://docs.oracle.com/javase/8/docs/api/java/util/function/BiConsumer.html), [P](../it.unibo.alchemist.boundary.interfaces/-draw-command/index.md)> <br>{@code OutputMonitor} that monitors the current [steps](../it.unibo.alchemist.core.interfaces/-simulation/get-step.md) of the {@code Simulation}. |
| [PlayPauseMonitor](-play-pause-monitor/index.md) | [jvm]<br>open class [PlayPauseMonitor](-play-pause-monitor/index.md)<[T](-play-pause-monitor/index.md), [P](-play-pause-monitor/index.md) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.md)<out [P](../it.unibo.alchemist.boundary.interfaces/-draw-command/index.md)>?> : JFXButton, [OutputMonitor](../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)<[T](https://docs.oracle.com/javase/8/docs/api/java/util/function/BiConsumer.html), [P](../it.unibo.alchemist.boundary.interfaces/-draw-command/index.md)> <br>{@code OutputMonitor} that monitors the current [status](../it.unibo.alchemist.core.interfaces/-status/index.md) of the {@code Simulation}, acting as a toggle to [play](../it.unibo.alchemist.core.interfaces/-simulation/play.md) and [pause](../it.unibo.alchemist.core.interfaces/-simulation/pause.md) the {@code Simulation}. |

//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.controller](../index.md)/[ButtonsBarController](index.md)/[ButtonsBarController](-buttons-bar-controller.md)

# ButtonsBarController

[jvm]\
open fun [ButtonsBarController](-buttons-bar-controller.md)()

Default constructor.

[jvm]\
open fun [ButtonsBarController](-buttons-bar-controller.md)(@Nullable()displayMonitor: @Nullable()[FXOutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-f-x-output-monitor/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)

Same as [default constructor](-buttons-bar-controller.md), but lets specify an [it.unibo.alchemist.boundary.interfaces.OutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md) to display the effects. 

 Useful to pass to [EffectsGroupBarController](../-effects-group-bar-controller/index.md), [EffectBarController](../-effect-bar-controller/index.md) and [EffectPropertiesController](../-effect-properties-controller/index.md).

## Parameters

jvm

| | |
|---|---|
| displayMonitor | the graphical {@code OutputMonitor} |

[jvm]\
open fun [ButtonsBarController](-buttons-bar-controller.md)(playPauseButton: Button, timeLabel: Label, stepLabel: Label)

Same as [default constructor](-buttons-bar-controller.md), but lets specify the play/pause Button, a Label for the steps and a Label for the time.

## Parameters

jvm

| | |
|---|---|
| playPauseButton | the play/pause {@code Button}; should probably be a [it.unibo.alchemist.boundary.monitor.PlayPauseMonitor](../../it.unibo.alchemist.boundary.monitor/-play-pause-monitor/index.md) |
| timeLabel | the {@code Label} for the steps; should probably be a [it.unibo.alchemist.boundary.monitor.generic.NumericLabelMonitor](../../it.unibo.alchemist.boundary.monitor.generic/-numeric-label-monitor/index.md) |
| stepLabel | the {@code Label} for the time; should probably be a [it.unibo.alchemist.boundary.monitor.generic.NumericLabelMonitor](../../it.unibo.alchemist.boundary.monitor.generic/-numeric-label-monitor/index.md) |

[jvm]\
open fun [ButtonsBarController](-buttons-bar-controller.md)(@Nullable()displayMonitor: @Nullable()[FXOutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-f-x-output-monitor/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, playPauseButton: Button, timeLabel: Label, stepLabel: Label)

Same as [default constructor](-buttons-bar-controller.md), but lets specify an [it.unibo.alchemist.boundary.interfaces.OutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md) to display the effects, the play/pause Button, a Label for the steps and a Label for the time. 

 Useful to pass to [EffectsGroupBarController](../-effects-group-bar-controller/index.md), [EffectBarController](../-effect-bar-controller/index.md) and [EffectPropertiesController](../-effect-properties-controller/index.md).

## Parameters

jvm

| | |
|---|---|
| displayMonitor | the graphical [it.unibo.alchemist.boundary.interfaces.OutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md) |
| playPauseButton | the play/pause {@code Button}; should probably be a [it.unibo.alchemist.boundary.monitor.PlayPauseMonitor](../../it.unibo.alchemist.boundary.monitor/-play-pause-monitor/index.md) |
| timeLabel | the {@code Label} for the steps; should probably be a [it.unibo.alchemist.boundary.monitor.generic.NumericLabelMonitor](../../it.unibo.alchemist.boundary.monitor.generic/-numeric-label-monitor/index.md) |
| stepLabel | the {@code Label} for the time; should probably be a [it.unibo.alchemist.boundary.monitor.generic.NumericLabelMonitor](../../it.unibo.alchemist.boundary.monitor.generic/-numeric-label-monitor/index.md) |

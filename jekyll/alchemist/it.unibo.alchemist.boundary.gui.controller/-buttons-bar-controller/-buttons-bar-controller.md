---
title: ButtonsBarController
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.controller](../index.html)/[ButtonsBarController](index.html)/[ButtonsBarController](-buttons-bar-controller.html)



# ButtonsBarController



[jvm]\
open fun [ButtonsBarController](-buttons-bar-controller.html)()



Default constructor.





[jvm]\
open fun [ButtonsBarController](-buttons-bar-controller.html)(@Nullable()displayMonitor: @Nullable()[FXOutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-f-x-output-monitor/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)



Same as [default constructor](-buttons-bar-controller.html), but lets specify an [it.unibo.alchemist.boundary.interfaces.OutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html) to display the effects. 



 Useful to pass to [EffectsGroupBarController](../-effects-group-bar-controller/index.html), [EffectBarController](../-effect-bar-controller/index.html) and [EffectPropertiesController](../-effect-properties-controller/index.html).



## Parameters


jvm

| | |
|---|---|
| displayMonitor | the graphical {@code OutputMonitor} |





[jvm]\
open fun [ButtonsBarController](-buttons-bar-controller.html)(playPauseButton: Button, timeLabel: Label, stepLabel: Label)



Same as [default constructor](-buttons-bar-controller.html), but lets specify the play/pause Button, a Label for the steps and a Label for the time.



## Parameters


jvm

| | |
|---|---|
| playPauseButton | the play/pause {@code Button}; should probably be a [it.unibo.alchemist.boundary.monitor.PlayPauseMonitor](../../it.unibo.alchemist.boundary.monitor/-play-pause-monitor/index.html) |
| timeLabel | the {@code Label} for the steps; should probably be a [it.unibo.alchemist.boundary.monitor.generic.NumericLabelMonitor](../../it.unibo.alchemist.boundary.monitor.generic/-numeric-label-monitor/index.html) |
| stepLabel | the {@code Label} for the time; should probably be a [it.unibo.alchemist.boundary.monitor.generic.NumericLabelMonitor](../../it.unibo.alchemist.boundary.monitor.generic/-numeric-label-monitor/index.html) |





[jvm]\
open fun [ButtonsBarController](-buttons-bar-controller.html)(@Nullable()displayMonitor: @Nullable()[FXOutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-f-x-output-monitor/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, playPauseButton: Button, timeLabel: Label, stepLabel: Label)



Same as [default constructor](-buttons-bar-controller.html), but lets specify an [it.unibo.alchemist.boundary.interfaces.OutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html) to display the effects, the play/pause Button, a Label for the steps and a Label for the time. 



 Useful to pass to [EffectsGroupBarController](../-effects-group-bar-controller/index.html), [EffectBarController](../-effect-bar-controller/index.html) and [EffectPropertiesController](../-effect-properties-controller/index.html).



## Parameters


jvm

| | |
|---|---|
| displayMonitor | the graphical [it.unibo.alchemist.boundary.interfaces.OutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html) |
| playPauseButton | the play/pause {@code Button}; should probably be a [it.unibo.alchemist.boundary.monitor.PlayPauseMonitor](../../it.unibo.alchemist.boundary.monitor/-play-pause-monitor/index.html) |
| timeLabel | the {@code Label} for the steps; should probably be a [it.unibo.alchemist.boundary.monitor.generic.NumericLabelMonitor](../../it.unibo.alchemist.boundary.monitor.generic/-numeric-label-monitor/index.html) |
| stepLabel | the {@code Label} for the time; should probably be a [it.unibo.alchemist.boundary.monitor.generic.NumericLabelMonitor](../../it.unibo.alchemist.boundary.monitor.generic/-numeric-label-monitor/index.html) |





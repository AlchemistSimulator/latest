---
title: ButtonsBarController
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.controller](../index.html)/[ButtonsBarController](index.html)



# ButtonsBarController



[jvm]\
open class [ButtonsBarController](index.html)<[P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-serializer/effect-from-file.html)>?> : Initializable

This class models a JavaFX controller for ButtonsBarLayout.fxml.



## Parameters


jvm

| | |
|---|---|
| <P> | the position type |



## Constructors


| | |
|---|---|
| [ButtonsBarController](-buttons-bar-controller.html) | [jvm]<br>open fun [ButtonsBarController](-buttons-bar-controller.html)()<br>Default constructor. |
| [ButtonsBarController](-buttons-bar-controller.html) | [jvm]<br>open fun [ButtonsBarController](-buttons-bar-controller.html)(@Nullable()displayMonitor: @Nullable()[FXOutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-f-x-output-monitor/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>Same as [default constructor](-buttons-bar-controller.html), but lets specify an [it.unibo.alchemist.boundary.interfaces.OutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html) to display the effects. |
| [ButtonsBarController](-buttons-bar-controller.html) | [jvm]<br>open fun [ButtonsBarController](-buttons-bar-controller.html)(playPauseButton: Button, timeLabel: Label, stepLabel: Label)<br>Same as [default constructor](-buttons-bar-controller.html), but lets specify the play/pause Button, a Label for the steps and a Label for the time. |
| [ButtonsBarController](-buttons-bar-controller.html) | [jvm]<br>open fun [ButtonsBarController](-buttons-bar-controller.html)(@Nullable()displayMonitor: @Nullable()[FXOutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-f-x-output-monitor/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, playPauseButton: Button, timeLabel: Label, stepLabel: Label)<br>Same as [default constructor](-buttons-bar-controller.html), but lets specify an [it.unibo.alchemist.boundary.interfaces.OutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html) to display the effects, the play/pause Button, a Label for the steps and a Label for the time. |


## Functions


| Name | Summary |
|---|---|
| [getObservableEffectsList](get-observable-effects-list.html) | [jvm]<br>open fun [getObservableEffectsList](get-observable-effects-list.html)(): ObservableList<[EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-serializer/effect-from-file.html)>><br>Getter method for the {@code List} of groups of [effects](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.html) in the side drawer. |
| [initialize](initialize.html) | [jvm]<br>open fun [initialize](initialize.html)(location: [URL](https://docs.oracle.com/javase/8/docs/api/java/net/URL.html), resources: [ResourceBundle](https://docs.oracle.com/javase/8/docs/api/java/util/ResourceBundle.html)) |
| [setStepMonitor](set-step-monitor.html) | [jvm]<br>fun [setStepMonitor](set-step-monitor.html)(stepMonitor: Label)<br>Sets the step monitor label. |
| [setTimeMonitor](set-time-monitor.html) | [jvm]<br>fun [setTimeMonitor](set-time-monitor.html)(timeMonitor: Label)<br>Sets the time monitor label. |


## Properties


| Name | Summary |
|---|---|
| [BUTTONS_BAR_LAYOUT](-b-u-t-t-o-n-s_-b-a-r_-l-a-y-o-u-t.html) | [jvm]<br>val [BUTTONS_BAR_LAYOUT](-b-u-t-t-o-n-s_-b-a-r_-l-a-y-o-u-t.html): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Layout path. |
| [displayMonitor](display-monitor.html) | [jvm]<br>private open var [displayMonitor](display-monitor.html): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[FXOutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-f-x-output-monitor/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>> |
| [startStopButton](start-stop-button.html) | [jvm]<br>@Nullable()<br>private open var [startStopButton](start-stop-button.html): @Nullable()Button |


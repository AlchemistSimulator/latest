//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.controller](../index.md)/[ButtonsBarController](index.md)

# ButtonsBarController

[jvm]\
open class [ButtonsBarController](index.md)<[P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.md)>?> : Initializable

This class models a JavaFX controller for ButtonsBarLayout.fxml.

## Parameters

jvm

| | |
|---|---|
| <P> | the position type |

## Constructors

| | |
|---|---|
| [ButtonsBarController](-buttons-bar-controller.md) | [jvm]<br>open fun [ButtonsBarController](-buttons-bar-controller.md)()<br>Default constructor. |
| [ButtonsBarController](-buttons-bar-controller.md) | [jvm]<br>open fun [ButtonsBarController](-buttons-bar-controller.md)(@Nullable()displayMonitor: @Nullable()[FXOutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-f-x-output-monitor/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>Same as [default constructor](-buttons-bar-controller.md), but lets specify an [it.unibo.alchemist.boundary.interfaces.OutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md) to display the effects. |
| [ButtonsBarController](-buttons-bar-controller.md) | [jvm]<br>open fun [ButtonsBarController](-buttons-bar-controller.md)(playPauseButton: Button, timeLabel: Label, stepLabel: Label)<br>Same as [default constructor](-buttons-bar-controller.md), but lets specify the play/pause Button, a Label for the steps and a Label for the time. |
| [ButtonsBarController](-buttons-bar-controller.md) | [jvm]<br>open fun [ButtonsBarController](-buttons-bar-controller.md)(@Nullable()displayMonitor: @Nullable()[FXOutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-f-x-output-monitor/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, playPauseButton: Button, timeLabel: Label, stepLabel: Label)<br>Same as [default constructor](-buttons-bar-controller.md), but lets specify an [it.unibo.alchemist.boundary.interfaces.OutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md) to display the effects, the play/pause Button, a Label for the steps and a Label for the time. |

## Functions

| Name | Summary |
|---|---|
| [getObservableEffectsList](get-observable-effects-list.md) | [jvm]<br>open fun [getObservableEffectsList](get-observable-effects-list.md)(): ObservableList<[EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.md)>><br>Getter method for the {@code List} of groups of [effects](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.md) in the side drawer. |
| [initialize](initialize.md) | [jvm]<br>open fun [initialize](initialize.md)(location: [URL](https://docs.oracle.com/javase/8/docs/api/java/net/URL.html), resources: [ResourceBundle](https://docs.oracle.com/javase/8/docs/api/java/util/ResourceBundle.html)) |
| [setStepMonitor](set-step-monitor.md) | [jvm]<br>fun [setStepMonitor](set-step-monitor.md)(stepMonitor: Label)<br>Sets the step monitor label. |
| [setTimeMonitor](set-time-monitor.md) | [jvm]<br>fun [setTimeMonitor](set-time-monitor.md)(timeMonitor: Label)<br>Sets the time monitor label. |

## Properties

| Name | Summary |
|---|---|
| [BUTTONS_BAR_LAYOUT](-b-u-t-t-o-n-s_-b-a-r_-l-a-y-o-u-t.md) | [jvm]<br>val [BUTTONS_BAR_LAYOUT](-b-u-t-t-o-n-s_-b-a-r_-l-a-y-o-u-t.md): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Layout path. |
| [displayMonitor](display-monitor.md) | [jvm]<br>private open var [displayMonitor](display-monitor.md): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[FXOutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-f-x-output-monitor/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>> |
| [startStopButton](start-stop-button.md) | [jvm]<br>@Nullable()<br>private open var [startStopButton](start-stop-button.md): @Nullable()Button |

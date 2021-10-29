//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.controller](../index.md)/[EffectsGroupBarController](index.md)

# EffectsGroupBarController

[jvm]\
open class [EffectsGroupBarController](index.md)<[P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>?> : Initializable

This class models a JavaFX controller for EffectsGroupBar.fxml.

## Parameters

jvm

| | |
|---|---|
| <P> | the position type |

## Constructors

| | |
|---|---|
| [EffectsGroupBarController](-effects-group-bar-controller.md) | [jvm]<br>open fun [EffectsGroupBarController](-effects-group-bar-controller.md)(stack: JFXDrawersStack)<br>Default constructor. |
| [EffectsGroupBarController](-effects-group-bar-controller.md) | [jvm]<br>open fun [EffectsGroupBarController](-effects-group-bar-controller.md)(@Nullable()displayMonitor: @Nullable()[FXOutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-f-x-output-monitor/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, stack: JFXDrawersStack)<br>Constructor. |

## Functions

| Name | Summary |
|---|---|
| [initialize](initialize.md) | [jvm]<br>open fun [initialize](initialize.md)(location: [URL](https://docs.oracle.com/javase/8/docs/api/java/net/URL.html), resources: [ResourceBundle](https://docs.oracle.com/javase/8/docs/api/java/util/ResourceBundle.html)) |

## Properties

| Name | Summary |
|---|---|
| [displayMonitor](display-monitor.md) | [jvm]<br>private open var [displayMonitor](display-monitor.md): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[FXOutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-f-x-output-monitor/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>> |
| [EFFECT_GROUP_BAR_LAYOUT](-e-f-f-e-c-t_-g-r-o-u-p_-b-a-r_-l-a-y-o-u-t.md) | [jvm]<br>val [EFFECT_GROUP_BAR_LAYOUT](-e-f-f-e-c-t_-g-r-o-u-p_-b-a-r_-l-a-y-o-u-t.md): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Layout path. |
| [observableEffectsList](observable-effects-list.md) | [jvm]<br>private open val [observableEffectsList](observable-effects-list.md): ObservableList<[EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>> |

---
title: EffectsGroupBarController
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.controller](../index.html)/[EffectsGroupBarController](index.html)



# EffectsGroupBarController



[jvm]\
open class [EffectsGroupBarController](index.html)<[P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)>?> : Initializable

This class models a JavaFX controller for EffectsGroupBar.fxml.



## Parameters


jvm

| | |
|---|---|
| <P> | the position type |



## Constructors


| | |
|---|---|
| [EffectsGroupBarController](-effects-group-bar-controller.html) | [jvm]<br>open fun [EffectsGroupBarController](-effects-group-bar-controller.html)(stack: JFXDrawersStack)<br>Default constructor. |
| [EffectsGroupBarController](-effects-group-bar-controller.html) | [jvm]<br>open fun [EffectsGroupBarController](-effects-group-bar-controller.html)(@Nullable()displayMonitor: @Nullable()[FXOutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-f-x-output-monitor/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, stack: JFXDrawersStack)<br>Constructor. |


## Functions


| Name | Summary |
|---|---|
| [initialize](initialize.html) | [jvm]<br>open fun [initialize](initialize.html)(location: [URL](https://docs.oracle.com/javase/8/docs/api/java/net/URL.html), resources: [ResourceBundle](https://docs.oracle.com/javase/8/docs/api/java/util/ResourceBundle.html)) |


## Properties


| Name | Summary |
|---|---|
| [displayMonitor](display-monitor.html) | [jvm]<br>private open var [displayMonitor](display-monitor.html): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[FXOutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-f-x-output-monitor/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>> |
| [EFFECT_GROUP_BAR_LAYOUT](-e-f-f-e-c-t_-g-r-o-u-p_-b-a-r_-l-a-y-o-u-t.html) | [jvm]<br>val [EFFECT_GROUP_BAR_LAYOUT](-e-f-f-e-c-t_-g-r-o-u-p_-b-a-r_-l-a-y-o-u-t.html): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Layout path. |
| [observableEffectsList](observable-effects-list.html) | [jvm]<br>private open val [observableEffectsList](observable-effects-list.html): ObservableList<[EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)>> |


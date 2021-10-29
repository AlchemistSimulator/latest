---
title: EffectBarController
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.controller](../index.html)/[EffectBarController](index.html)



# EffectBarController



[jvm]\
open class [EffectBarController](index.html)<[P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>?> : Initializable

This class models a JavaFX controller for EffectBar.fxml.



## Parameters


jvm

| | |
|---|---|
| <P> | the position type |



## Constructors


| | |
|---|---|
| [EffectBarController](-effect-bar-controller.html) | [jvm]<br>open fun [EffectBarController](-effect-bar-controller.html)(parentCell: [EffectGroupCell](../../it.unibo.alchemist.boundary.gui.view.cells/-effect-group-cell/index.html)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>, stack: JFXDrawersStack, thisDrawer: JFXDrawer)<br>Default constructor. |
| [EffectBarController](-effect-bar-controller.html) | [jvm]<br>open fun [EffectBarController](-effect-bar-controller.html)(@Nullable()displayMonitor: @Nullable()[FXOutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-f-x-output-monitor/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, parentCell: [EffectGroupCell](../../it.unibo.alchemist.boundary.gui.view.cells/-effect-group-cell/index.html)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>, stack: JFXDrawersStack, thisDrawer: JFXDrawer)<br>Constructor. |


## Functions


| Name | Summary |
|---|---|
| [addEffectToGroup](add-effect-to-group.html) | [jvm]<br>open fun [addEffectToGroup](add-effect-to-group.html)(effect: [EffectFX](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>)<br>Add the [Effect](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.html) to the ListView controlled by this class and to the [it.unibo.alchemist.boundary.gui.effects.EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html) that the GUI controlled by this claass is representation of. |
| [groupNameProperty](group-name-property.html) | [jvm]<br>open fun [groupNameProperty](group-name-property.html)(): StringProperty<br>The name property of this representation of the group. |
| [initialize](initialize.html) | [jvm]<br>open fun [initialize](initialize.html)(location: [URL](https://docs.oracle.com/javase/8/docs/api/java/net/URL.html), resources: [ResourceBundle](https://docs.oracle.com/javase/8/docs/api/java/util/ResourceBundle.html)) |


## Properties


| Name | Summary |
|---|---|
| [displayMonitor](display-monitor.html) | [jvm]<br>private open var [displayMonitor](display-monitor.html): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[FXOutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-f-x-output-monitor/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>> |
| [EFFECT_BAR_LAYOUT](-e-f-f-e-c-t_-b-a-r_-l-a-y-o-u-t.html) | [jvm]<br>val [EFFECT_BAR_LAYOUT](-e-f-f-e-c-t_-b-a-r_-l-a-y-o-u-t.html): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Layout path. |


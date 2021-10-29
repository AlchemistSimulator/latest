//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.controller](../index.md)/[EffectBarController](index.md)

# EffectBarController

[jvm]\
open class [EffectBarController](index.md)<[P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.md)>?> : Initializable

This class models a JavaFX controller for EffectBar.fxml.

## Parameters

jvm

| | |
|---|---|
| <P> | the position type |

## Constructors

| | |
|---|---|
| [EffectBarController](-effect-bar-controller.md) | [jvm]<br>open fun [EffectBarController](-effect-bar-controller.md)(parentCell: [EffectGroupCell](../../it.unibo.alchemist.boundary.gui.view.cells/-effect-group-cell/index.md)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.md)>, stack: JFXDrawersStack, thisDrawer: JFXDrawer)<br>Default constructor. |
| [EffectBarController](-effect-bar-controller.md) | [jvm]<br>open fun [EffectBarController](-effect-bar-controller.md)(@Nullable()displayMonitor: @Nullable()[FXOutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-f-x-output-monitor/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, parentCell: [EffectGroupCell](../../it.unibo.alchemist.boundary.gui.view.cells/-effect-group-cell/index.md)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.md)>, stack: JFXDrawersStack, thisDrawer: JFXDrawer)<br>Constructor. |

## Functions

| Name | Summary |
|---|---|
| [addEffectToGroup](add-effect-to-group.md) | [jvm]<br>open fun [addEffectToGroup](add-effect-to-group.md)(effect: [EffectFX](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.md)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.md)>)<br>Add the [Effect](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.md) to the ListView controlled by this class and to the [it.unibo.alchemist.boundary.gui.effects.EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md) that the GUI controlled by this claass is representation of. |
| [groupNameProperty](group-name-property.md) | [jvm]<br>open fun [groupNameProperty](group-name-property.md)(): StringProperty<br>The name property of this representation of the group. |
| [initialize](initialize.md) | [jvm]<br>open fun [initialize](initialize.md)(location: [URL](https://docs.oracle.com/javase/8/docs/api/java/net/URL.html), resources: [ResourceBundle](https://docs.oracle.com/javase/8/docs/api/java/util/ResourceBundle.html)) |

## Properties

| Name | Summary |
|---|---|
| [displayMonitor](display-monitor.md) | [jvm]<br>private open var [displayMonitor](display-monitor.md): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[FXOutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-f-x-output-monitor/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>> |
| [EFFECT_BAR_LAYOUT](-e-f-f-e-c-t_-b-a-r_-l-a-y-o-u-t.md) | [jvm]<br>val [EFFECT_BAR_LAYOUT](-e-f-f-e-c-t_-b-a-r_-l-a-y-o-u-t.md): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Layout path. |

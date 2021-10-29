//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.view](../index.md)/[SingleRunApp](index.md)

# SingleRunApp

[jvm]\
open class [SingleRunApp](index.md)<[T](index.md), [P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)>?> : Application

The class models a non-reusable GUI for simulation display.

## Parameters

jvm

| | |
|---|---|
| <T> | the [it.unibo.alchemist.model.interfaces.Concentration](../../it.unibo.alchemist.model.interfaces/-concentration/index.md) type |
| <P> | the position type |

## Functions

| Name | Summary |
|---|---|
| [addEffectGroups](add-effect-groups.md) | [jvm]<br>open fun [addEffectGroups](add-effect-groups.md)(path: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Adds effect from a file.<br>[jvm]<br>open fun [addEffectGroups](add-effect-groups.md)(effectGroups: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)>>)<br>Adds the effects to the current effects. |
| [addParam](add-param.md) | [jvm]<br>open fun [addParam](add-param.md)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), value: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>The method adds a new named parameter. |
| [getHostServices](../../it.unibo.alchemist.boundary/-keybinder/index.md#792481849%2FFunctions%2F-267951372) | [jvm]<br>fun [getHostServices](../../it.unibo.alchemist.boundary/-keybinder/index.md#792481849%2FFunctions%2F-267951372)(): HostServices |
| [getParameters](../../it.unibo.alchemist.boundary/-keybinder/index.md#-807279243%2FFunctions%2F-267951372) | [jvm]<br>fun [getParameters](../../it.unibo.alchemist.boundary/-keybinder/index.md#-807279243%2FFunctions%2F-267951372)(): Application.Parameters |
| [getUserAgentStylesheet](index.md#1310383795%2FFunctions%2F-267951372) | [jvm]<br>open fun [getUserAgentStylesheet](index.md#1310383795%2FFunctions%2F-267951372)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [init](../../it.unibo.alchemist.boundary/-keybinder/index.md#-1813461483%2FFunctions%2F-267951372) | [jvm]<br>open fun [init](../../it.unibo.alchemist.boundary/-keybinder/index.md#-1813461483%2FFunctions%2F-267951372)() |
| [launch](index.md#28279780%2FFunctions%2F-267951372) | [jvm]<br>open fun [launch](index.md#28279780%2FFunctions%2F-267951372)(p: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<out Application>, p1: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)>) |
| [notifyPreloader](index.md#-1908879305%2FFunctions%2F-267951372) | [jvm]<br>fun [notifyPreloader](index.md#-1908879305%2FFunctions%2F-267951372)(p: Preloader.PreloaderNotification) |
| [setUserAgentStylesheet](index.md#126481850%2FFunctions%2F-267951372) | [jvm]<br>open fun [setUserAgentStylesheet](index.md#126481850%2FFunctions%2F-267951372)(p: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)) |
| [start](start.md) | [jvm]<br>open fun [start](start.md)(primaryStage: Stage) |
| [stop](index.md#644806499%2FFunctions%2F-267951372) | [jvm]<br>open fun [stop](index.md#644806499%2FFunctions%2F-267951372)() |

## Properties

| Name | Summary |
|---|---|
| [effectGroups](effect-groups.md) | [jvm]<br>private open var [effectGroups](effect-groups.md): ObservableList<[EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)>> |
| [PARAMETER_NAME_END](-p-a-r-a-m-e-t-e-r_-n-a-m-e_-e-n-d.md) | [jvm]<br>val [PARAMETER_NAME_END](-p-a-r-a-m-e-t-e-r_-n-a-m-e_-e-n-d.md): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Default parameter end string. |
| [PARAMETER_NAME_START](-p-a-r-a-m-e-t-e-r_-n-a-m-e_-s-t-a-r-t.md) | [jvm]<br>val [PARAMETER_NAME_START](-p-a-r-a-m-e-t-e-r_-n-a-m-e_-s-t-a-r-t.md): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Default parameter start string. |
| [params](params.md) | [jvm]<br>private var [params](params.md): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)> |
| [ROOT_LAYOUT](-r-o-o-t_-l-a-y-o-u-t.md) | [jvm]<br>val [ROOT_LAYOUT](-r-o-o-t_-l-a-y-o-u-t.md): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Main layout without nested layouts. |
| [simulation](simulation.md) | [jvm]<br>@Nullable()<br>private open var [simulation](simulation.md): @Nullable()[Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.md)<[T](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.md), [P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)> |
| [USE_EFFECT_GROUPS_FROM_FILE](-u-s-e_-e-f-f-e-c-t_-g-r-o-u-p-s_-f-r-o-m_-f-i-l-e.md) | [jvm]<br>val [USE_EFFECT_GROUPS_FROM_FILE](-u-s-e_-e-f-f-e-c-t_-g-r-o-u-p-s_-f-r-o-m_-f-i-l-e.md): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Effect pass param name. |

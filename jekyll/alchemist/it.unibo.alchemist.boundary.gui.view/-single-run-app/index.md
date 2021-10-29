---
title: SingleRunApp
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.view](../index.html)/[SingleRunApp](index.html)



# SingleRunApp



[jvm]\
open class [SingleRunApp](index.html)<[T](index.html), [P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)>?> : Application

The class models a non-reusable GUI for simulation display.



## Parameters


jvm

| | |
|---|---|
| <T> | the [it.unibo.alchemist.model.interfaces.Concentration](../../it.unibo.alchemist.model.interfaces/-concentration/index.html) type |
| <P> | the position type |



## Functions


| Name | Summary |
|---|---|
| [addEffectGroups](add-effect-groups.html) | [jvm]<br>open fun [addEffectGroups](add-effect-groups.html)(path: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Adds effect from a file.<br>[jvm]<br>open fun [addEffectGroups](add-effect-groups.html)(effectGroups: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)>>)<br>Adds the effects to the current effects. |
| [addParam](add-param.html) | [jvm]<br>open fun [addParam](add-param.html)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), value: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>The method adds a new named parameter. |
| [getHostServices](../../it.unibo.alchemist.boundary/-keybinder/index.html#792481849%2FFunctions%2F-134779887) | [jvm]<br>fun [getHostServices](../../it.unibo.alchemist.boundary/-keybinder/index.html#792481849%2FFunctions%2F-134779887)(): HostServices |
| [getParameters](../../it.unibo.alchemist.boundary/-keybinder/index.html#-807279243%2FFunctions%2F-134779887) | [jvm]<br>fun [getParameters](../../it.unibo.alchemist.boundary/-keybinder/index.html#-807279243%2FFunctions%2F-134779887)(): Application.Parameters |
| [getUserAgentStylesheet](index.html#1310383795%2FFunctions%2F-134779887) | [jvm]<br>open fun [getUserAgentStylesheet](index.html#1310383795%2FFunctions%2F-134779887)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [init](../../it.unibo.alchemist.boundary/-keybinder/index.html#-1813461483%2FFunctions%2F-134779887) | [jvm]<br>open fun [init](../../it.unibo.alchemist.boundary/-keybinder/index.html#-1813461483%2FFunctions%2F-134779887)() |
| [launch](index.html#28279780%2FFunctions%2F-134779887) | [jvm]<br>open fun [launch](index.html#28279780%2FFunctions%2F-134779887)(p: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<out Application>, p1: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)>) |
| [notifyPreloader](index.html#-1908879305%2FFunctions%2F-134779887) | [jvm]<br>fun [notifyPreloader](index.html#-1908879305%2FFunctions%2F-134779887)(p: Preloader.PreloaderNotification) |
| [setUserAgentStylesheet](index.html#126481850%2FFunctions%2F-134779887) | [jvm]<br>open fun [setUserAgentStylesheet](index.html#126481850%2FFunctions%2F-134779887)(p: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)) |
| [start](start.html) | [jvm]<br>open fun [start](start.html)(primaryStage: Stage) |
| [stop](index.html#644806499%2FFunctions%2F-134779887) | [jvm]<br>open fun [stop](index.html#644806499%2FFunctions%2F-134779887)() |


## Properties


| Name | Summary |
|---|---|
| [effectGroups](effect-groups.html) | [jvm]<br>private open var [effectGroups](effect-groups.html): ObservableList<[EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)>> |
| [PARAMETER_NAME_END](-p-a-r-a-m-e-t-e-r_-n-a-m-e_-e-n-d.html) | [jvm]<br>val [PARAMETER_NAME_END](-p-a-r-a-m-e-t-e-r_-n-a-m-e_-e-n-d.html): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Default parameter end string. |
| [PARAMETER_NAME_START](-p-a-r-a-m-e-t-e-r_-n-a-m-e_-s-t-a-r-t.html) | [jvm]<br>val [PARAMETER_NAME_START](-p-a-r-a-m-e-t-e-r_-n-a-m-e_-s-t-a-r-t.html): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Default parameter start string. |
| [params](params.html) | [jvm]<br>private var [params](params.html): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)> |
| [ROOT_LAYOUT](-r-o-o-t_-l-a-y-o-u-t.html) | [jvm]<br>val [ROOT_LAYOUT](-r-o-o-t_-l-a-y-o-u-t.html): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Main layout without nested layouts. |
| [simulation](simulation.html) | [jvm]<br>@Nullable()<br>private open var [simulation](simulation.html): @Nullable()[Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.html)<[T](../../it.unibo.alchemist.boundary.gui.view.properties/-property-type-adapter/index.html), [P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)> |
| [USE_EFFECT_GROUPS_FROM_FILE](-u-s-e_-e-f-f-e-c-t_-g-r-o-u-p-s_-f-r-o-m_-f-i-l-e.html) | [jvm]<br>val [USE_EFFECT_GROUPS_FROM_FILE](-u-s-e_-e-f-f-e-c-t_-g-r-o-u-p-s_-f-r-o-m_-f-i-l-e.html): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Effect pass param name. |


---
title: WantToEscape
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.conditions](../index.html)/[WantToEscape](index.html)



# WantToEscape



[jvm]\
open class [WantToEscape](index.html)<[T](index.html), [S](index.html) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[S](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[S](index.html)>>(**pedestrian**: [CognitivePedestrian](../../it.unibo.alchemist.model.interfaces/-cognitive-pedestrian/index.html)<[T](index.html), [S](index.html), [A](index.html)>) : [AbstractCondition](../-abstract-condition/index.html)<[T](index.html)> 

The intention of the pedestrian to evacuate or not.



## Constructors


| | |
|---|---|
| [WantToEscape](-want-to-escape.html) | [jvm]<br>fun <[T](index.html), [S](index.html) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[S](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[S](index.html)>> [WantToEscape](-want-to-escape.html)(pedestrian: [CognitivePedestrian](../../it.unibo.alchemist.model.interfaces/-cognitive-pedestrian/index.html)<[T](index.html), [S](index.html), [A](index.html)>) |


## Functions


| Name | Summary |
|---|---|
| [cloneCondition](../-contains-molecule/index.html#1114898962%2FFunctions%2F-134779887) | [jvm]<br>open override fun [cloneCondition](../-contains-molecule/index.html#1114898962%2FFunctions%2F-134779887)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>): [Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.html)<[T](index.html)> |
| [declareDependencyOn](../-no-other-reaction-can-execute/index.html#-94060918%2FFunctions%2F-134779887) | [jvm]<br>fun [declareDependencyOn](../-no-other-reaction-can-execute/index.html#-94060918%2FFunctions%2F-134779887)(p0: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)) |
| [getContext](get-context.html) | [jvm]<br>open override fun [getContext](get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.html) | [jvm]<br>override fun [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [getNode](../-lsa-standard-condition/index.html#-1460695024%2FFunctions%2F-134779887) | [jvm]<br>open override fun [getNode](../-lsa-standard-condition/index.html#-1460695024%2FFunctions%2F-134779887)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)> |
| [getPropensityContribution](get-propensity-contribution.html) | [jvm]<br>open override fun [getPropensityContribution](get-propensity-contribution.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [isValid](is-valid.html) | [jvm]<br>open override fun [isValid](is-valid.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.html) | [jvm]<br>open fun [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.html)() |
| [toString](../-abstract-condition/to-string.html) | [jvm]<br>open override fun [toString](../-abstract-condition/to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |


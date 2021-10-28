//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.conditions](../index.md)/[WantToEscape](index.md)

# WantToEscape

[jvm]\
open class [WantToEscape](index.md)<[T](index.md), [S](index.md) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[S](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[S](index.md)>>(**pedestrian**: [CognitivePedestrian](../../it.unibo.alchemist.model.interfaces/-cognitive-pedestrian/index.md)<[T](index.md), [S](index.md), [A](index.md)>) : [AbstractCondition](../-abstract-condition/index.md)<[T](index.md)> 

The intention of the pedestrian to evacuate or not.

## Constructors

| | |
|---|---|
| [WantToEscape](-want-to-escape.md) | [jvm]<br>fun <[T](index.md), [S](index.md) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[S](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[S](index.md)>> [WantToEscape](-want-to-escape.md)(pedestrian: [CognitivePedestrian](../../it.unibo.alchemist.model.interfaces/-cognitive-pedestrian/index.md)<[T](index.md), [S](index.md), [A](index.md)>) |

## Functions

| Name | Summary |
|---|---|
| [cloneCondition](../-contains-molecule/index.md#1114898962%2FFunctions%2F-267951372) | [jvm]<br>open override fun [cloneCondition](../-contains-molecule/index.md#1114898962%2FFunctions%2F-267951372)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>): [Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.md)<[T](index.md)> |
| [declareDependencyOn](../-no-other-reaction-can-execute/index.md#-94060918%2FFunctions%2F-267951372) | [jvm]<br>fun [declareDependencyOn](../-no-other-reaction-can-execute/index.md#-94060918%2FFunctions%2F-267951372)(p0: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)) |
| [getContext](get-context.md) | [jvm]<br>open override fun [getContext](get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.md) | [jvm]<br>override fun [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [getNode](../-lsa-standard-condition/index.md#-1460695024%2FFunctions%2F-267951372) | [jvm]<br>open override fun [getNode](../-lsa-standard-condition/index.md#-1460695024%2FFunctions%2F-267951372)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)> |
| [getPropensityContribution](get-propensity-contribution.md) | [jvm]<br>open override fun [getPropensityContribution](get-propensity-contribution.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [isValid](is-valid.md) | [jvm]<br>open override fun [isValid](is-valid.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.md) | [jvm]<br>open fun [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.md)() |
| [toString](../-abstract-condition/to-string.md) | [jvm]<br>open override fun [toString](../-abstract-condition/to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
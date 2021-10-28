//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.conditions](../index.md)/[NoOtherReactionCanExecute](index.md)

# NoOtherReactionCanExecute

[jvm]\
class [NoOtherReactionCanExecute](index.md)<[T](index.md)>(**node**: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, **myReaction**: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>) : [AbstractCondition](../-abstract-condition/index.md)<[T](index.md)> 

The condition is valid if all the other reactions having at least one condition can not execute. This condition can be used only in a single reaction per node, as multiple instances would lead to undecidable situations.

## Constructors

| | |
|---|---|
| [NoOtherReactionCanExecute](-no-other-reaction-can-execute.md) | [jvm]<br>fun <[T](index.md)> [NoOtherReactionCanExecute](-no-other-reaction-can-execute.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, myReaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>) |

## Functions

| Name | Summary |
|---|---|
| [cloneCondition](clone-condition.md) | [jvm]<br>open override fun [cloneCondition](clone-condition.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>): [NoOtherReactionCanExecute](index.md)<[T](index.md)><br>How to override: create a new action of your concrete subtype. |
| [declareDependencyOn](index.md#-94060918%2FFunctions%2F-267951372) | [jvm]<br>fun [declareDependencyOn](index.md#-94060918%2FFunctions%2F-267951372)(m: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)) |
| [getContext](get-context.md) | [jvm]<br>open override fun [getContext](get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.md) | [jvm]<br>override fun [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [getNode](../-lsa-standard-condition/index.md#-1460695024%2FFunctions%2F-267951372) | [jvm]<br>open override fun [getNode](../-lsa-standard-condition/index.md#-1460695024%2FFunctions%2F-267951372)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)> |
| [getPropensityContribution](get-propensity-contribution.md) | [jvm]<br>open override fun [getPropensityContribution](get-propensity-contribution.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [isValid](is-valid.md) | [jvm]<br>open override fun [isValid](is-valid.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.md) | [jvm]<br>open fun [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.md)() |
| [toString](../-abstract-condition/to-string.md) | [jvm]<br>open override fun [toString](../-abstract-condition/to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

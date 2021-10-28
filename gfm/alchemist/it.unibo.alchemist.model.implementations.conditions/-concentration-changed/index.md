//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.conditions](../index.md)/[ConcentrationChanged](index.md)

# ConcentrationChanged

[jvm]\
class [ConcentrationChanged](index.md)<[T](index.md)> : [AbstractCondition](../-abstract-condition/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)> 

A condition that holds true only if the tracked [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md) changed its [it.unibo.alchemist.model.interfaces.Concentration](../../it.unibo.alchemist.model.interfaces/-concentration/index.md).

## Parameters

jvm

| | |
|---|---|
| <T> | concentration type |

## Constructors

| | |
|---|---|
| [ConcentrationChanged](-concentration-changed.md) | [jvm]<br>open fun [ConcentrationChanged](-concentration-changed.md)(@[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>, @[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()target: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md))<br>the node |

## Functions

| Name | Summary |
|---|---|
| [cloneCondition](clone-condition.md) | [jvm]<br>open fun [cloneCondition](clone-condition.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>): [ConcentrationChanged](index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)><br>How to override: create a new action of your concrete subtype.<br>[jvm]<br>abstract fun [cloneCondition](../../it.unibo.alchemist.model.interfaces/-condition/clone-condition.md)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>): [Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)> |
| [getContext](get-context.md) | [jvm]<br>open fun [getContext](get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.md) | [jvm]<br>fun [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)><br>How to override: if you intend your condition to be potentially changed by any change in the context, return null.<br>[jvm]<br>abstract fun [getInboundDependencies](../../it.unibo.alchemist.model.interfaces/-condition/get-inbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [getNode](../-lsa-standard-condition/index.md#-1460695024%2FFunctions%2F-267951372) | [jvm]<br>open fun [getNode](../-lsa-standard-condition/index.md#-1460695024%2FFunctions%2F-267951372)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)><br>Override if your [Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.md) can return a more specific type of node.<br>[jvm]<br>abstract fun [getNode](../../it.unibo.alchemist.model.interfaces/-condition/get-node.md)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)> |
| [getPropensityContribution](get-propensity-contribution.md) | [jvm]<br>open fun [getPropensityContribution](get-propensity-contribution.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [isValid](is-valid.md) | [jvm]<br>open fun [isValid](is-valid.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.md) | [jvm]<br>open fun [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.md)() |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>the simple class name |
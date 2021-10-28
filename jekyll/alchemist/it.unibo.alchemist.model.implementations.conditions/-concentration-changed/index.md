---
title: ConcentrationChanged
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.conditions](../index.html)/[ConcentrationChanged](index.html)



# ConcentrationChanged



[jvm]\
class [ConcentrationChanged](index.html)<[T](index.html)> : [AbstractCondition](../-abstract-condition/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)> 

A condition that holds true only if the tracked [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html) changed its [it.unibo.alchemist.model.interfaces.Concentration](../../it.unibo.alchemist.model.interfaces/-concentration/index.html).



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Constructors


| | |
|---|---|
| [ConcentrationChanged](-concentration-changed.html) | [jvm]<br>open fun [ConcentrationChanged](-concentration-changed.html)(@[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>, @[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()target: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html))<br>the node |


## Functions


| Name | Summary |
|---|---|
| [cloneCondition](clone-condition.html) | [jvm]<br>open fun [cloneCondition](clone-condition.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>): [ConcentrationChanged](index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)><br>How to override: create a new action of your concrete subtype.<br>[jvm]<br>abstract fun [cloneCondition](../../it.unibo.alchemist.model.interfaces/-condition/clone-condition.html)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>): [Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)> |
| [getContext](get-context.html) | [jvm]<br>open fun [getContext](get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.html) | [jvm]<br>fun [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)><br>How to override: if you intend your condition to be potentially changed by any change in the context, return null.<br>[jvm]<br>abstract fun [getInboundDependencies](../../it.unibo.alchemist.model.interfaces/-condition/get-inbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [getNode](../-lsa-standard-condition/index.html#-1460695024%2FFunctions%2F-134779887) | [jvm]<br>open fun [getNode](../-lsa-standard-condition/index.html#-1460695024%2FFunctions%2F-134779887)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)><br>Override if your [Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.html) can return a more specific type of node.<br>[jvm]<br>abstract fun [getNode](../../it.unibo.alchemist.model.interfaces/-condition/get-node.html)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)> |
| [getPropensityContribution](get-propensity-contribution.html) | [jvm]<br>open fun [getPropensityContribution](get-propensity-contribution.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [isValid](is-valid.html) | [jvm]<br>open fun [isValid](is-valid.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.html) | [jvm]<br>open fun [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.html)() |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>the simple class name |

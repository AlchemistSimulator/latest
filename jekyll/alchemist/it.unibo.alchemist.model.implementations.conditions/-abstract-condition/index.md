---
title: AbstractCondition
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.conditions](../index.html)/[AbstractCondition](index.html)



# AbstractCondition



[jvm]\
abstract class [AbstractCondition](index.html)<[T](index.html)> : [Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Constructors


| | |
|---|---|
| [AbstractCondition](-abstract-condition.html) | [jvm]<br>open fun [AbstractCondition](-abstract-condition.html)(@[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>)<br>the node this Condition belongs to |


## Functions


| Name | Summary |
|---|---|
| [cloneCondition](clone-condition.html) | [jvm]<br>open fun [cloneCondition](clone-condition.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>): [Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)><br>How to override: create a new action of your concrete subtype. |
| [getContext](../../it.unibo.alchemist.model.interfaces/-condition/get-context.html) | [jvm]<br>abstract fun [getContext](../../it.unibo.alchemist.model.interfaces/-condition/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getInboundDependencies](get-inbound-dependencies.html) | [jvm]<br>fun [getInboundDependencies](get-inbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)><br>How to override: if you intend your condition to be potentially changed by any change in the context, return null. |
| [getNode](../../it.unibo.alchemist.model.interfaces/-condition/get-node.html) | [jvm]<br>abstract fun [getNode](../../it.unibo.alchemist.model.interfaces/-condition/get-node.html)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)> |
| [getPropensityContribution](../../it.unibo.alchemist.model.interfaces/-condition/get-propensity-contribution.html) | [jvm]<br>abstract fun [getPropensityContribution](../../it.unibo.alchemist.model.interfaces/-condition/get-propensity-contribution.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [isValid](../../it.unibo.alchemist.model.interfaces/-condition/is-valid.html) | [jvm]<br>abstract fun [isValid](../../it.unibo.alchemist.model.interfaces/-condition/is-valid.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.html) | [jvm]<br>open fun [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.html)() |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>the simple class name |


## Properties


| Name | Summary |
|---|---|
| [node](node.html) | [jvm]<br>private val [node](node.html): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)> |


## Inheritors


| Name |
|---|
| [WantToEscape](../-want-to-escape/index.html) |
| [ConcentrationChanged](../-concentration-changed/index.html) |
| [MoleculeHasConcentration](../-molecule-has-concentration/index.html) |
| [ContainsMolecule](../-contains-molecule/index.html) |
| [NoOtherReactionCanExecute](../-no-other-reaction-can-execute/index.html) |
| [EnvPresent](../-env-present/index.html) |
| [AbstractNeighborCondition](../-abstract-neighbor-condition/index.html) |
| [TensionPresent](../-tension-present/index.html) |
| [GenericMoleculePresent](../-generic-molecule-present/index.html) |
| [ComputationalRoundComplete](../-computational-round-complete/index.html) |
| [LsaAbstractCondition](../-lsa-abstract-condition/index.html) |


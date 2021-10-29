//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.conditions](../index.md)/[AbstractCondition](index.md)

# AbstractCondition

[jvm]\
abstract class [AbstractCondition](index.md)<[T](index.md)> : [Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)>

## Parameters

jvm

| | |
|---|---|
| <T> | concentration type |

## Constructors

| | |
|---|---|
| [AbstractCondition](-abstract-condition.md) | [jvm]<br>open fun [AbstractCondition](-abstract-condition.md)(@[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)>)<br>the node this Condition belongs to |

## Functions

| Name | Summary |
|---|---|
| [cloneCondition](clone-condition.md) | [jvm]<br>open fun [cloneCondition](clone-condition.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)>): [Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)><br>How to override: create a new action of your concrete subtype. |
| [getContext](../../it.unibo.alchemist.model.interfaces/-condition/get-context.md) | [jvm]<br>abstract fun [getContext](../../it.unibo.alchemist.model.interfaces/-condition/get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getInboundDependencies](get-inbound-dependencies.md) | [jvm]<br>fun [getInboundDependencies](get-inbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)><br>How to override: if you intend your condition to be potentially changed by any change in the context, return null. |
| [getNode](../../it.unibo.alchemist.model.interfaces/-condition/get-node.md) | [jvm]<br>abstract fun [getNode](../../it.unibo.alchemist.model.interfaces/-condition/get-node.md)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)> |
| [getPropensityContribution](../../it.unibo.alchemist.model.interfaces/-condition/get-propensity-contribution.md) | [jvm]<br>abstract fun [getPropensityContribution](../../it.unibo.alchemist.model.interfaces/-condition/get-propensity-contribution.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [isValid](../../it.unibo.alchemist.model.interfaces/-condition/is-valid.md) | [jvm]<br>abstract fun [isValid](../../it.unibo.alchemist.model.interfaces/-condition/is-valid.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.md) | [jvm]<br>open fun [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.md)() |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>the simple class name |

## Properties

| Name | Summary |
|---|---|
| [node](node.md) | [jvm]<br>private val [node](node.md): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)> |

## Inheritors

| Name |
|---|
| [WantToEscape](../-want-to-escape/index.md) |
| [ConcentrationChanged](../-concentration-changed/index.md) |
| [MoleculeHasConcentration](../-molecule-has-concentration/index.md) |
| [ContainsMolecule](../-contains-molecule/index.md) |
| [NoOtherReactionCanExecute](../-no-other-reaction-can-execute/index.md) |
| [EnvPresent](../-env-present/index.md) |
| [AbstractNeighborCondition](../-abstract-neighbor-condition/index.md) |
| [TensionPresent](../-tension-present/index.md) |
| [GenericMoleculePresent](../-generic-molecule-present/index.md) |
| [ComputationalRoundComplete](../-computational-round-complete/index.md) |
| [LsaAbstractCondition](../-lsa-abstract-condition/index.md) |

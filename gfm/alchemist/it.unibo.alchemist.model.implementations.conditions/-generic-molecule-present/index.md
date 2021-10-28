//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.conditions](../index.md)/[GenericMoleculePresent](index.md)

# GenericMoleculePresent

[jvm]\
open class [GenericMoleculePresent](index.md)<[T](index.md) : [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)?> : [AbstractCondition](../-abstract-condition/index.md)<[T](../-neighborhood-present/index.md)> 

This class implements a condition which checks if a molecule is present or not.

## Parameters

jvm

| | |
|---|---|
| <T> | the concentration type |

## Constructors

| | |
|---|---|
| [GenericMoleculePresent](-generic-molecule-present.md) | [jvm]<br>open fun [GenericMoleculePresent](-generic-molecule-present.md)(n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../-neighborhood-present/index.md)>, mol: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), quantity: [T](../-neighborhood-present/index.md))<br>Builds a new condition, which checks if the molecule exists or not inside the node n. |

## Functions

| Name | Summary |
|---|---|
| [cloneCondition](clone-condition.md) | [jvm]<br>open fun [cloneCondition](clone-condition.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../-neighborhood-present/index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../-neighborhood-present/index.md)>): [GenericMoleculePresent](index.md)<[T](../-neighborhood-present/index.md)> |
| [getContext](get-context.md) | [jvm]<br>open fun [getContext](get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.md) | [jvm]<br>fun [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [getNode](../-lsa-standard-condition/index.md#-1460695024%2FFunctions%2F-267951372) | [jvm]<br>open fun [getNode](../-lsa-standard-condition/index.md#-1460695024%2FFunctions%2F-267951372)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../-neighborhood-present/index.md)> |
| [getPropensityContribution](get-propensity-contribution.md) | [jvm]<br>open fun [getPropensityContribution](get-propensity-contribution.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Propensity influence is computed through the binomial coefficient. |
| [getQuantity](get-quantity.md) | [jvm]<br>open fun [getQuantity](get-quantity.md)(): [T](../-neighborhood-present/index.md)<br>Allows to access the threshold. |
| [isValid](is-valid.md) | [jvm]<br>open fun [isValid](is-valid.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if the concentration of the molecule is higher or equal the value. |
| [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.md) | [jvm]<br>open fun [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.md)() |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

## Properties

| Name | Summary |
|---|---|
| [molecule](molecule.md) | [jvm]<br>private val [molecule](molecule.md): [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md) |

## Inheritors

| Name |
|---|
| [BiomolPresentInCell](../-biomol-present-in-cell/index.md) |
| [GenericMoleculeUnderLevel](../-generic-molecule-under-level/index.md) |
| [BiomolPresentInEnv](../-biomol-present-in-env/index.md) |

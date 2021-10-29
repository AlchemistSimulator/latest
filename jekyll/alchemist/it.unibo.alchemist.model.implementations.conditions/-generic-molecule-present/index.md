---
title: GenericMoleculePresent
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.conditions](../index.html)/[GenericMoleculePresent](index.html)



# GenericMoleculePresent



[jvm]\
open class [GenericMoleculePresent](index.html)<[T](index.html) : [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)?> : [AbstractCondition](../-abstract-condition/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-environment/index.html)> 

This class implements a condition which checks if a molecule is present or not.



## Parameters


jvm

| | |
|---|---|
| <T> | the concentration type |



## Constructors


| | |
|---|---|
| [GenericMoleculePresent](-generic-molecule-present.html) | [jvm]<br>open fun [GenericMoleculePresent](-generic-molecule-present.html)(n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-environment/index.html)>, mol: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), quantity: [T](../../it.unibo.alchemist.model.interfaces/-environment/index.html))<br>Builds a new condition, which checks if the molecule exists or not inside the node n. |


## Functions


| Name | Summary |
|---|---|
| [cloneCondition](clone-condition.html) | [jvm]<br>open fun [cloneCondition](clone-condition.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-environment/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-environment/index.html)>): [GenericMoleculePresent](index.html)<[T](../../it.unibo.alchemist.model.interfaces/-environment/index.html)> |
| [getContext](get-context.html) | [jvm]<br>open fun [getContext](get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.html) | [jvm]<br>fun [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [getNode](../-lsa-standard-condition/index.html#-1460695024%2FFunctions%2F-134779887) | [jvm]<br>open fun [getNode](../-lsa-standard-condition/index.html#-1460695024%2FFunctions%2F-134779887)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-environment/index.html)> |
| [getPropensityContribution](get-propensity-contribution.html) | [jvm]<br>open fun [getPropensityContribution](get-propensity-contribution.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Propensity influence is computed through the binomial coefficient. |
| [getQuantity](get-quantity.html) | [jvm]<br>open fun [getQuantity](get-quantity.html)(): [T](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<br>Allows to access the threshold. |
| [isValid](is-valid.html) | [jvm]<br>open fun [isValid](is-valid.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if the concentration of the molecule is higher or equal the value. |
| [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.html) | [jvm]<br>open fun [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.html)() |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Properties


| Name | Summary |
|---|---|
| [molecule](molecule.html) | [jvm]<br>private val [molecule](molecule.html): [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html) |


## Inheritors


| Name |
|---|
| [BiomolPresentInCell](../-biomol-present-in-cell/index.html) |
| [GenericMoleculeUnderLevel](../-generic-molecule-under-level/index.html) |
| [BiomolPresentInEnv](../-biomol-present-in-env/index.html) |


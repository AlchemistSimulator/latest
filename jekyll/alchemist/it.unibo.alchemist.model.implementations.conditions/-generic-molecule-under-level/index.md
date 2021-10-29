---
title: GenericMoleculeUnderLevel
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.conditions](../index.html)/[GenericMoleculeUnderLevel](index.html)



# GenericMoleculeUnderLevel



[jvm]\
class [GenericMoleculeUnderLevel](index.html)<[T](index.html) : [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)?> : [GenericMoleculePresent](../-generic-molecule-present/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-environment/index.html)>



## Parameters


jvm

| | |
|---|---|
| <T> | the concentration type |



## Constructors


| | |
|---|---|
| [GenericMoleculeUnderLevel](-generic-molecule-under-level.html) | [jvm]<br>open fun [GenericMoleculeUnderLevel](-generic-molecule-under-level.html)(n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-environment/index.html)>, mol: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), quantity: [T](../../it.unibo.alchemist.model.interfaces/-environment/index.html))<br>the molecule |


## Functions


| Name | Summary |
|---|---|
| [cloneCondition](../-abstract-condition/clone-condition.html) | [jvm]<br>open fun [cloneCondition](../-abstract-condition/clone-condition.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-environment/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-environment/index.html)>): [Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-environment/index.html)><br>open fun [cloneCondition](clone-condition.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-environment/index.html)>, r: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-environment/index.html)>): [GenericMoleculeUnderLevel](index.html)<[T](../../it.unibo.alchemist.model.interfaces/-environment/index.html)> |
| [getContext](../-generic-molecule-present/get-context.html) | [jvm]<br>open fun [getContext](../-generic-molecule-present/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html)<br>abstract fun [getContext](../../it.unibo.alchemist.model.interfaces/-condition/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.html) | [jvm]<br>fun [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [getMolecule](../-biomol-present-in-env/index.html#-310434243%2FFunctions%2F-134779887) | [jvm]<br>open fun [getMolecule](../-biomol-present-in-env/index.html#-310434243%2FFunctions%2F-134779887)(): [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)<br>Allows to access the molecule. |
| [getNode](../-lsa-standard-condition/index.html#-1460695024%2FFunctions%2F-134779887) | [jvm]<br>open fun [getNode](../-lsa-standard-condition/index.html#-1460695024%2FFunctions%2F-134779887)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.interfaces/-environment/index.html)> |
| [getPropensityContribution](get-propensity-contribution.html) | [jvm]<br>open fun [getPropensityContribution](get-propensity-contribution.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the propensity influence computed as max(0, T-[M]), where T is the threshold chosen and [M] is the current concentration of the molecule<br>[jvm]<br>abstract fun [getPropensityContribution](../../it.unibo.alchemist.model.interfaces/-condition/get-propensity-contribution.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getQuantity](../-generic-molecule-present/get-quantity.html) | [jvm]<br>open fun [getQuantity](../-generic-molecule-present/get-quantity.html)(): [T](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<br>Allows to access the threshold. |
| [isValid](is-valid.html) | [jvm]<br>open fun [isValid](is-valid.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if the concentration of the molecule is lower the value.<br>[jvm]<br>abstract fun [isValid](../../it.unibo.alchemist.model.interfaces/-condition/is-valid.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.html) | [jvm]<br>open fun [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.html)() |
| [toString](../-abstract-condition/to-string.html) | [jvm]<br>open fun [toString](../-abstract-condition/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>open fun [toString](../-generic-molecule-present/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


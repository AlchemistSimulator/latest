//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.conditions](../index.md)/[GenericMoleculeUnderLevel](index.md)

# GenericMoleculeUnderLevel

[jvm]\
class [GenericMoleculeUnderLevel](index.md)<[T](index.md) : [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)?> : [GenericMoleculePresent](../-generic-molecule-present/index.md)<[T](../-neighborhood-present/index.md)>

## Parameters

jvm

| | |
|---|---|
| <T> | the concentration type |

## Constructors

| | |
|---|---|
| [GenericMoleculeUnderLevel](-generic-molecule-under-level.md) | [jvm]<br>open fun [GenericMoleculeUnderLevel](-generic-molecule-under-level.md)(n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../-neighborhood-present/index.md)>, mol: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), quantity: [T](../-neighborhood-present/index.md))<br>the molecule |

## Functions

| Name | Summary |
|---|---|
| [cloneCondition](../-abstract-condition/clone-condition.md) | [jvm]<br>open fun [cloneCondition](../-abstract-condition/clone-condition.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../-neighborhood-present/index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../-neighborhood-present/index.md)>): [Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.md)<[T](../-neighborhood-present/index.md)><br>open fun [cloneCondition](clone-condition.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../-neighborhood-present/index.md)>, r: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../-neighborhood-present/index.md)>): [GenericMoleculeUnderLevel](index.md)<[T](../-neighborhood-present/index.md)> |
| [getContext](../-generic-molecule-present/get-context.md) | [jvm]<br>open fun [getContext](../-generic-molecule-present/get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md)<br>abstract fun [getContext](../../it.unibo.alchemist.model.interfaces/-condition/get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.md) | [jvm]<br>fun [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [getMolecule](../-biomol-present-in-env/index.md#-310434243%2FFunctions%2F-267951372) | [jvm]<br>open fun [getMolecule](../-biomol-present-in-env/index.md#-310434243%2FFunctions%2F-267951372)(): [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)<br>Allows to access the molecule. |
| [getNode](../-lsa-standard-condition/index.md#-1460695024%2FFunctions%2F-267951372) | [jvm]<br>open fun [getNode](../-lsa-standard-condition/index.md#-1460695024%2FFunctions%2F-267951372)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../-neighborhood-present/index.md)> |
| [getPropensityContribution](get-propensity-contribution.md) | [jvm]<br>open fun [getPropensityContribution](get-propensity-contribution.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the propensity influence computed as max(0, T-[M]), where T is the threshold chosen and [M] is the current concentration of the molecule<br>[jvm]<br>abstract fun [getPropensityContribution](../../it.unibo.alchemist.model.interfaces/-condition/get-propensity-contribution.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getQuantity](../-generic-molecule-present/get-quantity.md) | [jvm]<br>open fun [getQuantity](../-generic-molecule-present/get-quantity.md)(): [T](../-neighborhood-present/index.md)<br>Allows to access the threshold. |
| [isValid](is-valid.md) | [jvm]<br>open fun [isValid](is-valid.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if the concentration of the molecule is lower the value.<br>[jvm]<br>abstract fun [isValid](../../it.unibo.alchemist.model.interfaces/-condition/is-valid.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.md) | [jvm]<br>open fun [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.md)() |
| [toString](../-abstract-condition/to-string.md) | [jvm]<br>open fun [toString](../-abstract-condition/to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>open fun [toString](../-generic-molecule-present/to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

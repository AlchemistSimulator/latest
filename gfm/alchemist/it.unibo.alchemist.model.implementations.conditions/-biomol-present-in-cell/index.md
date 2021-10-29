//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.conditions](../index.md)/[BiomolPresentInCell](index.md)

# BiomolPresentInCell

[jvm]\
open class [BiomolPresentInCell](index.md) : [GenericMoleculePresent](../-generic-molecule-present/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>

## Constructors

| | |
|---|---|
| [BiomolPresentInCell](-biomol-present-in-cell.md) | [jvm]<br>open fun [BiomolPresentInCell](-biomol-present-in-cell.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, biomol: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), concentration: [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html))<br>the molecule |

## Functions

| Name | Summary |
|---|---|
| [cloneCondition](../-abstract-condition/clone-condition.md) | [jvm]<br>open fun [cloneCondition](../-abstract-condition/clone-condition.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.reactions/-chemical-reaction/index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.reactions/-chemical-reaction/index.md)>): [Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.md)<[T](../../it.unibo.alchemist.model.implementations.reactions/-chemical-reaction/index.md)><br>open fun [cloneCondition](../-generic-molecule-present/clone-condition.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.reactions/-chemical-reaction/index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.reactions/-chemical-reaction/index.md)>): [GenericMoleculePresent](../-generic-molecule-present/index.md)<[T](../../it.unibo.alchemist.model.implementations.reactions/-chemical-reaction/index.md)> |
| [getContext](../-generic-molecule-present/get-context.md) | [jvm]<br>open fun [getContext](../-generic-molecule-present/get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md)<br>abstract fun [getContext](../../it.unibo.alchemist.model.interfaces/-condition/get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.md) | [jvm]<br>fun [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [getMolecule](../-biomol-present-in-env/index.md#-310434243%2FFunctions%2F-267951372) | [jvm]<br>open fun [getMolecule](../-biomol-present-in-env/index.md#-310434243%2FFunctions%2F-267951372)(): [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)<br>Allows to access the molecule. |
| [getNode](../-lsa-standard-condition/index.md#-1460695024%2FFunctions%2F-267951372) | [jvm]<br>open fun [getNode](../-lsa-standard-condition/index.md#-1460695024%2FFunctions%2F-267951372)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.reactions/-chemical-reaction/index.md)> |
| [getPropensityContribution](../-generic-molecule-present/get-propensity-contribution.md) | [jvm]<br>open fun [getPropensityContribution](../-generic-molecule-present/get-propensity-contribution.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Propensity influence is computed through the binomial coefficient.<br>[jvm]<br>abstract fun [getPropensityContribution](../../it.unibo.alchemist.model.interfaces/-condition/get-propensity-contribution.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getQuantity](../-generic-molecule-present/get-quantity.md) | [jvm]<br>open fun [getQuantity](../-generic-molecule-present/get-quantity.md)(): [T](../../it.unibo.alchemist.model.implementations.reactions/-chemical-reaction/index.md)<br>Allows to access the threshold. |
| [isValid](../-generic-molecule-present/is-valid.md) | [jvm]<br>open fun [isValid](../-generic-molecule-present/is-valid.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if the concentration of the molecule is higher or equal the value.<br>[jvm]<br>abstract fun [isValid](../../it.unibo.alchemist.model.interfaces/-condition/is-valid.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.md) | [jvm]<br>open fun [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.md)() |
| [toString](../-abstract-condition/to-string.md) | [jvm]<br>open fun [toString](../-abstract-condition/to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>open fun [toString](../-generic-molecule-present/to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

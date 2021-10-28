//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[ChangeBiomolConcentrationInCell](index.md)

# ChangeBiomolConcentrationInCell

[jvm]\
class [ChangeBiomolConcentrationInCell](index.md) : [AbstractActionOnSingleMolecule](../-abstract-action-on-single-molecule/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>

## Constructors

| | |
|---|---|
| [ChangeBiomolConcentrationInCell](-change-biomol-concentration-in-cell.md) | [jvm]<br>open fun [ChangeBiomolConcentrationInCell](-change-biomol-concentration-in-cell.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, biomolecule: [Biomolecule](../../it.unibo.alchemist.model.implementations.molecules/-biomolecule/index.md), deltaConcentration: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>the molecule |

## Functions

| Name | Summary |
|---|---|
| [cloneAction](clone-action.md) | [jvm]<br>open fun [cloneAction](clone-action.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>): [ChangeBiomolConcentrationInCell](index.md) |
| [execute](execute.md) | [jvm]<br>open fun [execute](execute.md)() |
| [getContext](get-context.md) | [jvm]<br>open fun [getContext](get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getMolecule](../-abstract-action-on-single-molecule/get-molecule.md) | [jvm]<br>open fun [getMolecule](../-abstract-action-on-single-molecule/get-molecule.md)(): [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

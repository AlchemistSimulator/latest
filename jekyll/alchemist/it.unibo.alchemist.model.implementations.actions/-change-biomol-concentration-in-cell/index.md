---
title: ChangeBiomolConcentrationInCell
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[ChangeBiomolConcentrationInCell](index.html)



# ChangeBiomolConcentrationInCell



[jvm]\
class [ChangeBiomolConcentrationInCell](index.html) : [AbstractActionOnSingleMolecule](../-abstract-action-on-single-molecule/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>



## Constructors


| | |
|---|---|
| [ChangeBiomolConcentrationInCell](-change-biomol-concentration-in-cell.html) | [jvm]<br>open fun [ChangeBiomolConcentrationInCell](-change-biomol-concentration-in-cell.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, biomolecule: [Biomolecule](../../it.unibo.alchemist.model.implementations.molecules/-biomolecule/index.html), deltaConcentration: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>the molecule |


## Functions


| Name | Summary |
|---|---|
| [cloneAction](clone-action.html) | [jvm]<br>open fun [cloneAction](clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>): [ChangeBiomolConcentrationInCell](index.html) |
| [execute](execute.html) | [jvm]<br>open fun [execute](execute.html)() |
| [getContext](get-context.html) | [jvm]<br>open fun [getContext](get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getMolecule](../-abstract-action-on-single-molecule/get-molecule.html) | [jvm]<br>open fun [getMolecule](../-abstract-action-on-single-molecule/get-molecule.html)(): [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


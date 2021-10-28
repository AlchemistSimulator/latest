---
title: ChemotacticPolarization
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[ChemotacticPolarization](index.html)



# ChemotacticPolarization



[jvm]\
class [ChemotacticPolarization](index.html)<[P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>?> : [AbstractAction](../-abstract-action/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>



## Parameters


jvm

| | |
|---|---|
| <P> | [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html) type |



## Constructors


| | |
|---|---|
| [ChemotacticPolarization](-chemotactic-polarization.html) | [jvm]<br>open fun [ChemotacticPolarization](-chemotactic-polarization.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>, node: [CellNode](../../it.unibo.alchemist.model.interfaces/-cell-node/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>, biomolecule: [Biomolecule](../../it.unibo.alchemist.model.implementations.molecules/-biomolecule/index.html), ascendGrad: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>the environment |
| [ChemotacticPolarization](-chemotactic-polarization.html) | [jvm]<br>open fun [ChemotacticPolarization](-chemotactic-polarization.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, biomolecule: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), ascendGrad: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Initialize a polarization activity regulated by environmental concentration of a molecule. |


## Functions


| Name | Summary |
|---|---|
| [cloneAction](clone-action.html) | [jvm]<br>open fun [cloneAction](clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>): [ChemotacticPolarization](index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)> |
| [execute](execute.html) | [jvm]<br>open fun [execute](execute.html)() |
| [getContext](get-context.html) | [jvm]<br>open fun [getContext](get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getNode](get-node.html) | [jvm]<br>open fun [getNode](get-node.html)(): [CellNode](../../it.unibo.alchemist.model.interfaces/-cell-node/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)> |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [toString](../-abstract-action/to-string.html) | [jvm]<br>open fun [toString](../-abstract-action/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


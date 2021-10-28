---
title: CellTensionPolarization
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[CellTensionPolarization](index.html)



# CellTensionPolarization



[jvm]\
class [CellTensionPolarization](index.html)<[P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>?> : [AbstractAction](../-abstract-action/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>



## Parameters


jvm

| | |
|---|---|
| <P> | [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html) type |



## Constructors


| | |
|---|---|
| [CellTensionPolarization](-cell-tension-polarization.html) | [jvm]<br>open fun [CellTensionPolarization](-cell-tension-polarization.html)(environment: [EnvironmentSupportingDeformableCells](../../it.unibo.alchemist.model.interfaces/-environment-supporting-deformable-cells/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>, node: [CircularDeformableCell](../../it.unibo.alchemist.model.interfaces/-circular-deformable-cell/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>)<br>the node |


## Functions


| Name | Summary |
|---|---|
| [cloneAction](clone-action.html) | [jvm]<br>open fun [cloneAction](clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>): [CellTensionPolarization](index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)> |
| [execute](execute.html) | [jvm]<br>open fun [execute](execute.html)() |
| [getContext](get-context.html) | [jvm]<br>open fun [getContext](get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getNode](get-node.html) | [jvm]<br>open fun [getNode](get-node.html)(): [CircularDeformableCell](../../it.unibo.alchemist.model.interfaces/-circular-deformable-cell/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)> |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [toString](../-abstract-action/to-string.html) | [jvm]<br>open fun [toString](../-abstract-action/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


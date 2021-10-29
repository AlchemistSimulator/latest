//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[CellTensionPolarization](index.md)

# CellTensionPolarization

[jvm]\
class [CellTensionPolarization](index.md)<[P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.md)>?> : [AbstractAction](../-abstract-action/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>

## Parameters

jvm

| | |
|---|---|
| <P> | [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md) type |

## Constructors

| | |
|---|---|
| [CellTensionPolarization](-cell-tension-polarization.md) | [jvm]<br>open fun [CellTensionPolarization](-cell-tension-polarization.md)(environment: [EnvironmentSupportingDeformableCells](../../it.unibo.alchemist.model.interfaces/-environment-supporting-deformable-cells/index.md)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.md)>, node: [CircularDeformableCell](../../it.unibo.alchemist.model.interfaces/-circular-deformable-cell/index.md)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.md)>)<br>the node |

## Functions

| Name | Summary |
|---|---|
| [cloneAction](clone-action.md) | [jvm]<br>open fun [cloneAction](clone-action.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>): [CellTensionPolarization](index.md)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.md)> |
| [execute](execute.md) | [jvm]<br>open fun [execute](execute.md)() |
| [getContext](get-context.md) | [jvm]<br>open fun [getContext](get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getNode](get-node.md) | [jvm]<br>open fun [getNode](get-node.md)(): [CircularDeformableCell](../../it.unibo.alchemist.model.interfaces/-circular-deformable-cell/index.md)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.md)> |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [toString](../-abstract-action/to-string.md) | [jvm]<br>open fun [toString](../-abstract-action/to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

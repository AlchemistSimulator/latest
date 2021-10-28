//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[AbstractActionOnSingleMolecule](index.md)

# AbstractActionOnSingleMolecule

[jvm]\
abstract class [AbstractActionOnSingleMolecule](index.md)<[T](index.md)> : [AbstractAction](../-abstract-action/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)> 

This class offers the basic structures to provide operations with numeric concentrations on a single molecule.

## Parameters

jvm

| | |
|---|---|
| <T> | concentration type |

## Functions

| Name | Summary |
|---|---|
| [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.md) | [jvm]<br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.md)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)> |
| [execute](../../it.unibo.alchemist.model.interfaces/-action/execute.md) | [jvm]<br>abstract fun [execute](../../it.unibo.alchemist.model.interfaces/-action/execute.md)() |
| [getContext](../../it.unibo.alchemist.model.interfaces/-action/get-context.md) | [jvm]<br>abstract fun [getContext](../../it.unibo.alchemist.model.interfaces/-action/get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getMolecule](get-molecule.md) | [jvm]<br>open fun [getMolecule](get-molecule.md)(): [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)<br>the molecule which whose concentration will be modified y the execution of this action |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)><br>How to override: if you intend your action to influence any reaction with compatible context, return null.<br>[jvm]<br>abstract fun [getOutboundDependencies](../../it.unibo.alchemist.model.interfaces/-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [toString](../-abstract-action/to-string.md) | [jvm]<br>open fun [toString](../-abstract-action/to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

## Inheritors

| Name |
|---|
| [SetLocalMoleculeConcentration](../-set-local-molecule-concentration/index.md) |
| [ChangeBiomolConcentrationInCell](../-change-biomol-concentration-in-cell/index.md) |

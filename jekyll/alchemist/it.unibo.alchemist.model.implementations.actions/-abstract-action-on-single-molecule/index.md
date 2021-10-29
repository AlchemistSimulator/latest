---
title: AbstractActionOnSingleMolecule
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[AbstractActionOnSingleMolecule](index.html)



# AbstractActionOnSingleMolecule



[jvm]\
abstract class [AbstractActionOnSingleMolecule](index.html)<[T](index.html)> : [AbstractAction](../-abstract-action/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)> 

This class offers the basic structures to provide operations with numeric concentrations on a single molecule.



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Functions


| Name | Summary |
|---|---|
| [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.html) | [jvm]<br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.html)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)> |
| [execute](../../it.unibo.alchemist.model.interfaces/-action/execute.html) | [jvm]<br>abstract fun [execute](../../it.unibo.alchemist.model.interfaces/-action/execute.html)() |
| [getContext](../../it.unibo.alchemist.model.interfaces/-action/get-context.html) | [jvm]<br>abstract fun [getContext](../../it.unibo.alchemist.model.interfaces/-action/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getMolecule](get-molecule.html) | [jvm]<br>open fun [getMolecule](get-molecule.html)(): [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)<br>the molecule which whose concentration will be modified y the execution of this action |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)><br>How to override: if you intend your action to influence any reaction with compatible context, return null.<br>[jvm]<br>abstract fun [getOutboundDependencies](../../it.unibo.alchemist.model.interfaces/-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [toString](../-abstract-action/to-string.html) | [jvm]<br>open fun [toString](../-abstract-action/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Inheritors


| Name |
|---|
| [SetLocalMoleculeConcentration](../-set-local-molecule-concentration/index.html) |
| [ChangeBiomolConcentrationInCell](../-change-biomol-concentration-in-cell/index.html) |


---
title: SetLocalMoleculeConcentration
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[SetLocalMoleculeConcentration](index.html)



# SetLocalMoleculeConcentration



[jvm]\
class [SetLocalMoleculeConcentration](index.html)<[T](index.html)> : [AbstractActionOnSingleMolecule](../-abstract-action-on-single-molecule/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)>



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Constructors


| | |
|---|---|
| [SetLocalMoleculeConcentration](-set-local-molecule-concentration.html) | [jvm]<br>open fun [SetLocalMoleculeConcentration](-set-local-molecule-concentration.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)>, target: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), value: [T](../../it.unibo.alchemist/-supported-incarnations/get.html))<br>The node to which this action belongs |


## Functions


| Name | Summary |
|---|---|
| [cloneAction](clone-action.html) | [jvm]<br>open fun [cloneAction](clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)> |
| [execute](execute.html) | [jvm]<br>open fun [execute](execute.html)() |
| [getContext](get-context.html) | [jvm]<br>open fun [getContext](get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getMolecule](../-abstract-action-on-single-molecule/get-molecule.html) | [jvm]<br>open fun [getMolecule](../-abstract-action-on-single-molecule/get-molecule.html)(): [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)<br>the molecule which whose concentration will be modified y the execution of this action |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)><br>How to override: if you intend your action to influence any reaction with compatible context, return null.<br>[jvm]<br>abstract fun [getOutboundDependencies](../../it.unibo.alchemist.model.interfaces/-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [toString](../-abstract-action/to-string.html) | [jvm]<br>open fun [toString](../-abstract-action/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


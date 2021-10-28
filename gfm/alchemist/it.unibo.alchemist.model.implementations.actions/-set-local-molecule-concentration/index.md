//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[SetLocalMoleculeConcentration](index.md)

# SetLocalMoleculeConcentration

[jvm]\
class [SetLocalMoleculeConcentration](index.md)<[T](index.md)> : [AbstractActionOnSingleMolecule](../-abstract-action-on-single-molecule/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)>

## Parameters

jvm

| | |
|---|---|
| <T> | concentration type |

## Constructors

| | |
|---|---|
| [SetLocalMoleculeConcentration](-set-local-molecule-concentration.md) | [jvm]<br>open fun [SetLocalMoleculeConcentration](-set-local-molecule-concentration.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)>, target: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), value: [T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md))<br>The node to which this action belongs |

## Functions

| Name | Summary |
|---|---|
| [cloneAction](clone-action.md) | [jvm]<br>open fun [cloneAction](clone-action.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)> |
| [execute](execute.md) | [jvm]<br>open fun [execute](execute.md)() |
| [getContext](get-context.md) | [jvm]<br>open fun [getContext](get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getMolecule](../-abstract-action-on-single-molecule/get-molecule.md) | [jvm]<br>open fun [getMolecule](../-abstract-action-on-single-molecule/get-molecule.md)(): [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)<br>the molecule which whose concentration will be modified y the execution of this action |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)><br>How to override: if you intend your action to influence any reaction with compatible context, return null.<br>[jvm]<br>abstract fun [getOutboundDependencies](../../it.unibo.alchemist.model.interfaces/-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [toString](../-abstract-action/to-string.md) | [jvm]<br>open fun [toString](../-abstract-action/to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

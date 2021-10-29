//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[AbstractRandomizableAction](index.md)

# AbstractRandomizableAction

[jvm]\
abstract class [AbstractRandomizableAction](index.md)<[T](index.md)> : [AbstractAction](../-abstract-action/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)>

## Parameters

jvm

| | |
|---|---|
| <T> | concentration type |

## Constructors

| | |
|---|---|
| [AbstractRandomizableAction](-abstract-randomizable-action.md) | [jvm]<br>open fun [AbstractRandomizableAction](-abstract-randomizable-action.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)>, random: RandomGenerator)<br>the [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md) |

## Functions

| Name | Summary |
|---|---|
| [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.md) | [jvm]<br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.md)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)> |
| [execute](../../it.unibo.alchemist.model.interfaces/-action/execute.md) | [jvm]<br>abstract fun [execute](../../it.unibo.alchemist.model.interfaces/-action/execute.md)() |
| [getContext](../../it.unibo.alchemist.model.interfaces/-action/get-context.md) | [jvm]<br>abstract fun [getContext](../../it.unibo.alchemist.model.interfaces/-action/get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [toString](../-abstract-action/to-string.md) | [jvm]<br>open fun [toString](../-abstract-action/to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

## Inheritors

| Name |
|---|
| [RandomPolarization](../-random-polarization/index.md) |
| [AbstractNeighborAction](../-abstract-neighbor-action/index.md) |
| [ChangeBiomolConcentrationInEnv](../-change-biomol-concentration-in-env/index.md) |

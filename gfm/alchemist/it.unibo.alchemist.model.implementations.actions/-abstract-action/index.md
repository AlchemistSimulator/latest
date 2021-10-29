//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[AbstractAction](index.md)

# AbstractAction

[jvm]\
abstract class [AbstractAction](index.md)<[T](index.md)> : [Action](../../it.unibo.alchemist.model.interfaces/-action/index.md)<[T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md)> 

An abstract class facility with some generic methods implemented.

## Parameters

jvm

| | |
|---|---|
| <T> | concentration type |

## Functions

| Name | Summary |
|---|---|
| [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.md) | [jvm]<br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.md)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.md)<[T](../../it.unibo.alchemist.model.implementations.timedistributions/-weibull-distributed-weibull-time/index.md)> |
| [execute](../../it.unibo.alchemist.model.interfaces/-action/execute.md) | [jvm]<br>abstract fun [execute](../../it.unibo.alchemist.model.interfaces/-action/execute.md)() |
| [getContext](../../it.unibo.alchemist.model.interfaces/-action/get-context.md) | [jvm]<br>abstract fun [getContext](../../it.unibo.alchemist.model.interfaces/-action/get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getOutboundDependencies](get-outbound-dependencies.md) | [jvm]<br>fun [getOutboundDependencies](get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)><br>How to override: if you intend your action to influence any reaction with compatible context, return null. |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

## Inheritors

| Name |
|---|
| [FollowAtDistance](../-follow-at-distance/index.md) |
| [HeadTowardRandomDirection](../-head-toward-random-direction/index.md) |
| [HeadTowardTarget](../-head-toward-target/index.md) |
| [Spin](../-spin/index.md) |
| [RemoveNode](../-remove-node/index.md) |
| [AbstractLocalAction](../-abstract-local-action/index.md) |
| [AbstractActionOnSingleMolecule](../-abstract-action-on-single-molecule/index.md) |
| [AbstractMoveNode](../-abstract-move-node/index.md) |
| [ToggleMolecule](../-toggle-molecule/index.md) |
| [AbstractRandomizableAction](../-abstract-randomizable-action/index.md) |
| [ChemotacticPolarization](../-chemotactic-polarization/index.md) |
| [CellTensionPolarization](../-cell-tension-polarization/index.md) |
| [SendToNeighbor](../-send-to-neighbor/index.md) |
| [LsaAbstractAction](../-lsa-abstract-action/index.md) |
| [CameraInjectVisibleNodeClosestToDistance](../-camera-inject-visible-node-closest-to-distance/index.md) |
| [CameraSee](../-camera-see/index.md) |

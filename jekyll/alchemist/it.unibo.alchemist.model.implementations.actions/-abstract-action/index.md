---
title: AbstractAction
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[AbstractAction](index.html)



# AbstractAction



[jvm]\
abstract class [AbstractAction](index.html)<[T](index.html)> : [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)> 

An abstract class facility with some generic methods implemented.



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Functions


| Name | Summary |
|---|---|
| [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.html) | [jvm]<br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.html)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)> |
| [execute](../../it.unibo.alchemist.model.interfaces/-action/execute.html) | [jvm]<br>abstract fun [execute](../../it.unibo.alchemist.model.interfaces/-action/execute.html)() |
| [getContext](../../it.unibo.alchemist.model.interfaces/-action/get-context.html) | [jvm]<br>abstract fun [getContext](../../it.unibo.alchemist.model.interfaces/-action/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getOutboundDependencies](get-outbound-dependencies.html) | [jvm]<br>fun [getOutboundDependencies](get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)><br>How to override: if you intend your action to influence any reaction with compatible context, return null. |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Inheritors


| Name |
|---|
| [FollowAtDistance](../-follow-at-distance/index.html) |
| [HeadTowardRandomDirection](../-head-toward-random-direction/index.html) |
| [HeadTowardTarget](../-head-toward-target/index.html) |
| [Spin](../-spin/index.html) |
| [RemoveNode](../-remove-node/index.html) |
| [AbstractLocalAction](../-abstract-local-action/index.html) |
| [AbstractActionOnSingleMolecule](../-abstract-action-on-single-molecule/index.html) |
| [AbstractMoveNode](../-abstract-move-node/index.html) |
| [ToggleMolecule](../-toggle-molecule/index.html) |
| [AbstractRandomizableAction](../-abstract-randomizable-action/index.html) |
| [ChemotacticPolarization](../-chemotactic-polarization/index.html) |
| [CellTensionPolarization](../-cell-tension-polarization/index.html) |
| [SendToNeighbor](../-send-to-neighbor/index.html) |
| [LsaAbstractAction](../-lsa-abstract-action/index.html) |
| [CameraInjectVisibleNodeClosestToDistance](../-camera-inject-visible-node-closest-to-distance/index.html) |
| [CameraSee](../-camera-see/index.html) |


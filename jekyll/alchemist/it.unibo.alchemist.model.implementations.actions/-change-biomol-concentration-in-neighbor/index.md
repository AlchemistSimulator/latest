---
title: ChangeBiomolConcentrationInNeighbor
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[ChangeBiomolConcentrationInNeighbor](index.html)



# ChangeBiomolConcentrationInNeighbor



[jvm]\
class [ChangeBiomolConcentrationInNeighbor](index.html) : [AbstractNeighborAction](../-abstract-neighbor-action/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>



## Constructors


| | |
|---|---|
| [ChangeBiomolConcentrationInNeighbor](-change-biomol-concentration-in-neighbor.html) | [jvm]<br>open fun [ChangeBiomolConcentrationInNeighbor](-change-biomol-concentration-in-neighbor.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, biomolecule: [Biomolecule](../../it.unibo.alchemist.model.implementations.molecules/-biomolecule/index.html), randGen: RandomGenerator, deltaConcentration: [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html))<br>the molecule |


## Functions


| Name | Summary |
|---|---|
| [cloneAction](clone-action.html) | [jvm]<br>open fun [cloneAction](clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>): [ChangeBiomolConcentrationInNeighbor](index.html)<br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.html)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.html)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.html)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.html)> |
| [execute](execute.html) | [jvm]<br>open fun [execute](execute.html)()<br>Execute the action on a random neighbor if the node has a neighborhood.<br>[jvm]<br>abstract fun [execute](../../it.unibo.alchemist.model.interfaces/-action/execute.html)()<br>[jvm]<br>open fun [execute](execute.html)(targetNode: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>)<br>Execute the action on the given target node. |
| [getContext](../-abstract-neighbor-action/get-context.html) | [jvm]<br>fun [getContext](../-abstract-neighbor-action/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html)<br>abstract fun [getContext](../../it.unibo.alchemist.model.interfaces/-action/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[ChangeBiomolConcentrationInNeighbor](index.md)

# ChangeBiomolConcentrationInNeighbor

[jvm]\
class [ChangeBiomolConcentrationInNeighbor](index.md) : [AbstractNeighborAction](../-abstract-neighbor-action/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>

## Constructors

| | |
|---|---|
| [ChangeBiomolConcentrationInNeighbor](-change-biomol-concentration-in-neighbor.md) | [jvm]<br>open fun [ChangeBiomolConcentrationInNeighbor](-change-biomol-concentration-in-neighbor.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, biomolecule: [Biomolecule](../../it.unibo.alchemist.model.implementations.molecules/-biomolecule/index.md), randGen: RandomGenerator, deltaConcentration: [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html))<br>the molecule |

## Functions

| Name | Summary |
|---|---|
| [cloneAction](clone-action.md) | [jvm]<br>open fun [cloneAction](clone-action.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>): [ChangeBiomolConcentrationInNeighbor](index.md)<br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.md)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.environments/-limited-continuos2-d/index.md)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.environments/-limited-continuos2-d/index.md)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.md)<[T](../../it.unibo.alchemist.model.implementations.environments/-limited-continuos2-d/index.md)> |
| [execute](execute.md) | [jvm]<br>open fun [execute](execute.md)()<br>Execute the action on a random neighbor if the node has a neighborhood.<br>[jvm]<br>abstract fun [execute](../../it.unibo.alchemist.model.interfaces/-action/execute.md)()<br>[jvm]<br>open fun [execute](execute.md)(targetNode: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>)<br>Execute the action on the given target node. |
| [getContext](../-abstract-neighbor-action/get-context.md) | [jvm]<br>fun [getContext](../-abstract-neighbor-action/get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md)<br>abstract fun [getContext](../../it.unibo.alchemist.model.interfaces/-action/get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

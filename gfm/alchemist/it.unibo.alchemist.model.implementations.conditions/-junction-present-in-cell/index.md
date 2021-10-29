//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.conditions](../index.md)/[JunctionPresentInCell](index.md)

# JunctionPresentInCell

[jvm]\
class [JunctionPresentInCell](index.md) : [AbstractNeighborCondition](../-abstract-neighbor-condition/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>

## Constructors

| | |
|---|---|
| [JunctionPresentInCell](-junction-present-in-cell.md) | [jvm]<br>open fun [JunctionPresentInCell](-junction-present-in-cell.md)(e: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, junction: [Junction](../../it.unibo.alchemist.model.implementations.molecules/-junction/index.md))<br>the junction |

## Functions

| Name | Summary |
|---|---|
| [cloneCondition](../-abstract-condition/clone-condition.md) | [jvm]<br>open fun [cloneCondition](../-abstract-condition/clone-condition.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../-generic-molecule-present/index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../-generic-molecule-present/index.md)>): [Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.md)<[T](../-generic-molecule-present/index.md)><br>open fun [cloneCondition](clone-condition.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, r: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>): [JunctionPresentInCell](index.md) |
| [getContext](../-abstract-neighbor-condition/get-context.md) | [jvm]<br>fun [getContext](../-abstract-neighbor-condition/get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md)<br>abstract fun [getContext](../../it.unibo.alchemist.model.interfaces/-condition/get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.md) | [jvm]<br>fun [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [getNode](get-node.md) | [jvm]<br>open fun [getNode](get-node.md)(): [CellNode](../../it.unibo.alchemist.model.interfaces/-cell-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [getPropensityContribution](../-abstract-neighbor-condition/get-propensity-contribution.md) | [jvm]<br>open fun [getPropensityContribution](../-abstract-neighbor-condition/get-propensity-contribution.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Override if desired behavior differs.<br>[jvm]<br>abstract fun [getPropensityContribution](../../it.unibo.alchemist.model.interfaces/-condition/get-propensity-contribution.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getValidNeighbors](../-abstract-neighbor-condition/get-valid-neighbors.md) | [jvm]<br>fun [getValidNeighbors](../-abstract-neighbor-condition/get-valid-neighbors.md)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../-generic-molecule-present/index.md)>, [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)><br>Searches in the given neighborhood which nodes satisfy the condition, and returns a list of valid neighbors. |
| [isValid](is-valid.md) | [jvm]<br>open fun [isValid](is-valid.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.md) | [jvm]<br>open fun [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.md)() |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

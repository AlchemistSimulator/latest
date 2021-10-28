//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[EnvironmentSupportingDeformableCells](index.md)

# EnvironmentSupportingDeformableCells

[jvm]\
interface [EnvironmentSupportingDeformableCells](index.md)<[P](index.md) : [Position](../-position/index.md)<out [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.md)>?> : [Environment](../-environment/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.md)> 

[Environment](../-environment/index.md) supporting deformable cells.

## Parameters

jvm

| | |
|---|---|
| <P> | position type |

## Functions

| Name | Summary |
|---|---|
| [addLayer](../-environment/add-layer.md) | [jvm]<br>abstract fun [addLayer](../-environment/add-layer.md)(p: [Molecule](../-molecule/index.md), p1: [Layer](../-layer/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md), [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.md)>) |
| [addNode](../-environment/add-node.md) | [jvm]<br>abstract fun [addNode](../-environment/add-node.md)(p: [Node](../-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)>, p1: [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.md)) |
| [addTerminator](../-environment/add-terminator.md) | [jvm]<br>abstract fun [addTerminator](../-environment/add-terminator.md)(p: [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](../-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md), [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.md)>>) |
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getDimensions](../-environment/get-dimensions.md) | [jvm]<br>abstract fun [getDimensions](../-environment/get-dimensions.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getDistanceBetweenNodes](../-environment/get-distance-between-nodes.md) | [jvm]<br>abstract fun [getDistanceBetweenNodes](../-environment/get-distance-between-nodes.md)(p: [Node](../-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)>, p1: [Node](../-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)>): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getIncarnation](../-environment/get-incarnation.md) | [jvm]<br>abstract fun [getIncarnation](../-environment/get-incarnation.md)(): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Incarnation](../-incarnation/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md), [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.md)>> |
| [getLayer](../-environment/get-layer.md) | [jvm]<br>abstract fun [getLayer](../-environment/get-layer.md)(p: [Molecule](../-molecule/index.md)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Layer](../-layer/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md), [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.md)>> |
| [getLayers](../-environment/get-layers.md) | [jvm]<br>abstract fun [getLayers](../-environment/get-layers.md)(): ListSet<[Layer](../-layer/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md), [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.md)>> |
| [getLinkingRule](../-environment/get-linking-rule.md) | [jvm]<br>abstract fun [getLinkingRule](../-environment/get-linking-rule.md)(): [LinkingRule](../-linking-rule/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md), [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.md)> |
| [getMaxDiameterAmongCircularDeformableCells](get-max-diameter-among-circular-deformable-cells.md) | [jvm]<br>abstract fun [getMaxDiameterAmongCircularDeformableCells](get-max-diameter-among-circular-deformable-cells.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the biggest among the deformable cell's diameter, when not stressed. |
| [getNeighborhood](../-environment/get-neighborhood.md) | [jvm]<br>abstract fun [getNeighborhood](../-environment/get-neighborhood.md)(p: [Node](../-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)>): [Neighborhood](../-neighborhood/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)> |
| [getNodeByID](../-environment/get-node-by-i-d.md) | [jvm]<br>abstract fun [getNodeByID](../-environment/get-node-by-i-d.md)(p: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Node](../-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)> |
| [getNodeCount](../-environment/get-node-count.md) | [jvm]<br>abstract fun [getNodeCount](../-environment/get-node-count.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getNodes](../-environment/get-nodes.md) | [jvm]<br>abstract fun [getNodes](../-environment/get-nodes.md)(): ListSet<[Node](../-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)>> |
| [getNodesWithinRange](../-environment/get-nodes-within-range.md) | [jvm]<br>abstract fun [getNodesWithinRange](../-environment/get-nodes-within-range.md)(p: [Node](../-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)>, p1: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): ListSet<[Node](../-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)>> |
| [getOffset](../-environment/get-offset.md) | [jvm]<br>abstract fun [getOffset](../-environment/get-offset.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [getPosition](../-environment/get-position.md) | [jvm]<br>abstract fun [getPosition](../-environment/get-position.md)(p: [Node](../-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)>): [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.md) |
| [getSimulation](../-environment/get-simulation.md) | [jvm]<br>abstract fun [getSimulation](../-environment/get-simulation.md)(): [Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md), [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.md)> |
| [getSize](../-environment/get-size.md) | [jvm]<br>abstract fun [getSize](../-environment/get-size.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [getSizeInDistanceUnits](../-environment/get-size-in-distance-units.md) | [jvm]<br>abstract fun [getSizeInDistanceUnits](../-environment/get-size-in-distance-units.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [isTerminated](../-environment/is-terminated.md) | [jvm]<br>abstract fun [isTerminated](../-environment/is-terminated.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)> |
| [makePosition](../-environment/make-position.md) | [jvm]<br>abstract fun [makePosition](../-environment/make-position.md)(p: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)>): [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.md) |
| [moveNodeToPosition](../-environment/move-node-to-position.md) | [jvm]<br>abstract fun [moveNodeToPosition](../-environment/move-node-to-position.md)(p: [Node](../-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)>, p1: [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.md)) |
| [removeNode](../-environment/remove-node.md) | [jvm]<br>abstract fun [removeNode](../-environment/remove-node.md)(p: [Node](../-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)>) |
| [setLinkingRule](../-environment/set-linking-rule.md) | [jvm]<br>abstract fun [setLinkingRule](../-environment/set-linking-rule.md)(p: [LinkingRule](../-linking-rule/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md), [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.md)>) |
| [setSimulation](../-environment/set-simulation.md) | [jvm]<br>abstract fun [setSimulation](../-environment/set-simulation.md)(p: [Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md), [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.md)>) |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-neighborhood-present/index.md)> |

## Inheritors

| Name |
|---|
| [BioRect2DEnvironmentNoOverlap](../../it.unibo.alchemist.model.implementations.environments/-bio-rect2-d-environment-no-overlap/index.md) |
//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Environment](index.md)

# Environment

[jvm]\
interface [Environment](index.md)<[T](index.md), [P](index.md) : [Position](../-position/index.md)<out [P](../-incarnation/index.md)>?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)<[Node](../-node/index.md)<[T](../-node/index.md)>> 

Interface for an environment. Every environment must implement this specification.

## Parameters

jvm

| | |
|---|---|
| <P> | Concentration type |
| <T> | Position type |

## Functions

| Name | Summary |
|---|---|
| [addLayer](add-layer.md) | [jvm]<br>abstract fun [addLayer](add-layer.md)(m: [Molecule](../-molecule/index.md), l: [Layer](../-layer/index.md)<[T](../-node/index.md), [P](../-incarnation/index.md)>)<br>Add a [Layer](../-layer/index.md) to the [Environment](index.md). |
| [addNode](add-node.md) | [jvm]<br>abstract fun [addNode](add-node.md)(node: [Node](../-node/index.md)<[T](../-node/index.md)>, p: [P](../-incarnation/index.md))<br>This method allows to add a new node to this environment. |
| [addTerminator](add-terminator.md) | [jvm]<br>abstract fun [addTerminator](add-terminator.md)(terminator: [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](index.md)<[T](../-node/index.md), [P](../-incarnation/index.md)>>)<br>a [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html) indicating whether the simulation should be considered finished |
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getDimensions](get-dimensions.md) | [jvm]<br>abstract fun [getDimensions](get-dimensions.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The number of dimensions of this environment. |
| [getDistanceBetweenNodes](get-distance-between-nodes.md) | [jvm]<br>abstract fun [getDistanceBetweenNodes](get-distance-between-nodes.md)(n1: [Node](../-node/index.md)<[T](../-node/index.md)>, n2: [Node](../-node/index.md)<[T](../-node/index.md)>): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Measures the distance between two nodes in the environment. |
| [getIncarnation](get-incarnation.md) | [jvm]<br>abstract fun [getIncarnation](get-incarnation.md)(): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Incarnation](../-incarnation/index.md)<[T](../-node/index.md), [P](../-incarnation/index.md)>><br>the [Incarnation](../-incarnation/index.md) used to initialize the entities of this [Environment](index.md), if it has been set. |
| [getLayer](get-layer.md) | [jvm]<br>abstract fun [getLayer](get-layer.md)(m: [Molecule](../-molecule/index.md)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Layer](../-layer/index.md)<[T](../-node/index.md), [P](../-incarnation/index.md)>><br>Get the layer associate to the given molecule. |
| [getLayers](get-layers.md) | [jvm]<br>abstract fun [getLayers](get-layers.md)(): ListSet<[Layer](../-layer/index.md)<[T](../-node/index.md), [P](../-incarnation/index.md)>><br>Return all the Layers in this [Environment](index.md). |
| [getLinkingRule](get-linking-rule.md) | [jvm]<br>abstract fun [getLinkingRule](get-linking-rule.md)(): [LinkingRule](../-linking-rule/index.md)<[T](../-node/index.md), [P](../-incarnation/index.md)><br>the current linking rule |
| [getNeighborhood](get-neighborhood.md) | [jvm]<br>abstract fun [getNeighborhood](get-neighborhood.md)(center: [Node](../-node/index.md)<[T](../-node/index.md)>): [Neighborhood](../-neighborhood/index.md)<[T](../-node/index.md)><br>Given a node, this method returns its neighborhood. |
| [getNodeByID](get-node-by-i-d.md) | [jvm]<br>abstract fun [getNodeByID](get-node-by-i-d.md)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Node](../-node/index.md)<[T](../-node/index.md)><br>Allows to access a node known its id. |
| [getNodeCount](get-node-count.md) | [jvm]<br>abstract fun [getNodeCount](get-node-count.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the number of nodes currently in the environment |
| [getNodes](get-nodes.md) | [jvm]<br>abstract fun [getNodes](get-nodes.md)(): ListSet<[Node](../-node/index.md)<[T](../-node/index.md)>><br>All the nodes that exist in current environment. |
| [getNodesWithinRange](get-nodes-within-range.md) | [jvm]<br>abstract fun [getNodesWithinRange](get-nodes-within-range.md)(center: [P](../-incarnation/index.md), range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): ListSet<[Node](../-node/index.md)<[T](../-node/index.md)>><br>Given a [Position](../-position/index.md)(center) this method returns a list of all the surroundings nodes within the given range.<br>[jvm]<br>abstract fun [getNodesWithinRange](get-nodes-within-range.md)(center: [Node](../-node/index.md)<[T](../-node/index.md)>, range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): ListSet<[Node](../-node/index.md)<[T](../-node/index.md)>><br>Given a node (center) this method returns a list of all the surroundings nodes within the given range. |
| [getOffset](get-offset.md) | [jvm]<br>abstract fun [getOffset](get-offset.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)><br>This method allows to know which are the smallest coordinates represented. |
| [getPosition](get-position.md) | [jvm]<br>abstract fun [getPosition](get-position.md)(node: [Node](../-node/index.md)<[T](../-node/index.md)>): [P](../-incarnation/index.md)<br>Calculates the position of a node. |
| [getSimulation](get-simulation.md) | [jvm]<br>abstract fun [getSimulation](get-simulation.md)(): [Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.md)<[T](../-node/index.md), [P](../-incarnation/index.md)><br>the current simulation, if present, or throws an [IllegalStateException](https://docs.oracle.com/javase/8/docs/api/java/lang/IllegalStateException.html) otherwise |
| [getSize](get-size.md) | [jvm]<br>abstract fun [getSize](get-size.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)><br>This method returns the size of the environment as an array of length [getDimensions](get-dimensions.md). |
| [getSizeInDistanceUnits](get-size-in-distance-units.md) | [jvm]<br>abstract fun [getSizeInDistanceUnits](get-size-in-distance-units.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)><br>This method returns the size of the environment as an array of length [getDimensions](get-dimensions.md). |
| [isTerminated](is-terminated.md) | [jvm]<br>abstract fun [isTerminated](is-terminated.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if all the terminators are true |
| [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../-node/index.md)> |
| [makePosition](make-position.md) | [jvm]<br>abstract fun [makePosition](make-position.md)(coordinates: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)>): [P](../-incarnation/index.md)<br>the coordinates of the point |
| [moveNodeToPosition](move-node-to-position.md) | [jvm]<br>abstract fun [moveNodeToPosition](move-node-to-position.md)(node: [Node](../-node/index.md)<[T](../-node/index.md)>, position: [P](../-incarnation/index.md))<br>This method moves a node in the environment to some position. |
| [removeNode](remove-node.md) | [jvm]<br>abstract fun [removeNode](remove-node.md)(node: [Node](../-node/index.md)<[T](../-node/index.md)>)<br>This method allows to remove a node. |
| [setLinkingRule](set-linking-rule.md) | [jvm]<br>abstract fun [setLinkingRule](set-linking-rule.md)(rule: [LinkingRule](../-linking-rule/index.md)<[T](../-node/index.md), [P](../-incarnation/index.md)>)<br>the rule to set |
| [setSimulation](set-simulation.md) | [jvm]<br>abstract fun [setSimulation](set-simulation.md)(s: [Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.md)<[T](../-node/index.md), [P](../-incarnation/index.md)>)<br>the simulation |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../-node/index.md)> |

## Inheritors

| Name |
|---|
| [AbstractEnvironment](../../it.unibo.alchemist.model.implementations.environments/-abstract-environment/index.md) |
| [EnvironmentSupportingDeformableCells](../-environment-supporting-deformable-cells/index.md) |
| [BenchmarkableEnvironment](../-benchmarkable-environment/index.md) |
| [EuclideanEnvironment](../-euclidean-environment/index.md) |

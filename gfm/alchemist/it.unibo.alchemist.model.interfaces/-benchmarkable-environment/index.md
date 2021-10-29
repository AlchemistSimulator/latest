//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[BenchmarkableEnvironment](index.md)

# BenchmarkableEnvironment

[jvm]\
interface [BenchmarkableEnvironment](index.md)<[T](index.md), [P](index.md) : [Position](../-position/index.md)<out [P](../-incarnation/index.md)>?> : [Environment](../-environment/index.md)<[T](../-node/index.md), [P](../-incarnation/index.md)> 

An environment which provides a mean to get infos about its performances.

## Parameters

jvm

| | |
|---|---|
| <T> | Concentration type |
| <P> | [Position](../-position/index.md) type |

## Functions

| Name | Summary |
|---|---|
| [addLayer](../-environment/add-layer.md) | [jvm]<br>abstract fun [addLayer](../-environment/add-layer.md)(m: [Molecule](../-molecule/index.md), l: [Layer](../-layer/index.md)<[T](../-node/index.md), [P](../-incarnation/index.md)>)<br>Add a [Layer](../-layer/index.md) to the [Environment](../-environment/index.md). |
| [addNode](../-environment/add-node.md) | [jvm]<br>abstract fun [addNode](../-environment/add-node.md)(node: [Node](../-node/index.md)<[T](../-node/index.md)>, p: [P](../-incarnation/index.md))<br>This method allows to add a new node to this environment. |
| [addTerminator](../-environment/add-terminator.md) | [jvm]<br>abstract fun [addTerminator](../-environment/add-terminator.md)(terminator: [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](../-environment/index.md)<[T](../-node/index.md), [P](../-incarnation/index.md)>>)<br>a [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html) indicating whether the simulation should be considered finished |
| [enableBenchmark](enable-benchmark.md) | [jvm]<br>abstract fun [enableBenchmark](enable-benchmark.md)()<br>Call this method to tell this environment that it should record its performances. |
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getBenchmarkResult](get-benchmark-result.md) | [jvm]<br>abstract fun [getBenchmarkResult](get-benchmark-result.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>a double which is a index of the performances |
| [getDimensions](../-environment/get-dimensions.md) | [jvm]<br>abstract fun [getDimensions](../-environment/get-dimensions.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The number of dimensions of this environment. |
| [getDistanceBetweenNodes](../-environment/get-distance-between-nodes.md) | [jvm]<br>abstract fun [getDistanceBetweenNodes](../-environment/get-distance-between-nodes.md)(n1: [Node](../-node/index.md)<[T](../-node/index.md)>, n2: [Node](../-node/index.md)<[T](../-node/index.md)>): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Measures the distance between two nodes in the environment. |
| [getIncarnation](../-environment/get-incarnation.md) | [jvm]<br>abstract fun [getIncarnation](../-environment/get-incarnation.md)(): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Incarnation](../-incarnation/index.md)<[T](../-node/index.md), [P](../-incarnation/index.md)>><br>the [Incarnation](../-incarnation/index.md) used to initialize the entities of this [Environment](../-environment/index.md), if it has been set. |
| [getLayer](../-environment/get-layer.md) | [jvm]<br>abstract fun [getLayer](../-environment/get-layer.md)(m: [Molecule](../-molecule/index.md)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Layer](../-layer/index.md)<[T](../-node/index.md), [P](../-incarnation/index.md)>><br>Get the layer associate to the given molecule. |
| [getLayers](../-environment/get-layers.md) | [jvm]<br>abstract fun [getLayers](../-environment/get-layers.md)(): ListSet<[Layer](../-layer/index.md)<[T](../-node/index.md), [P](../-incarnation/index.md)>><br>Return all the Layers in this [Environment](../-environment/index.md). |
| [getLinkingRule](../-environment/get-linking-rule.md) | [jvm]<br>abstract fun [getLinkingRule](../-environment/get-linking-rule.md)(): [LinkingRule](../-linking-rule/index.md)<[T](../-node/index.md), [P](../-incarnation/index.md)><br>the current linking rule |
| [getNeighborhood](../-environment/get-neighborhood.md) | [jvm]<br>abstract fun [getNeighborhood](../-environment/get-neighborhood.md)(center: [Node](../-node/index.md)<[T](../-node/index.md)>): [Neighborhood](../-neighborhood/index.md)<[T](../-node/index.md)><br>Given a node, this method returns its neighborhood. |
| [getNodeByID](../-environment/get-node-by-i-d.md) | [jvm]<br>abstract fun [getNodeByID](../-environment/get-node-by-i-d.md)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Node](../-node/index.md)<[T](../-node/index.md)><br>Allows to access a node known its id. |
| [getNodeCount](../-environment/get-node-count.md) | [jvm]<br>abstract fun [getNodeCount](../-environment/get-node-count.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the number of nodes currently in the environment |
| [getNodes](../-environment/get-nodes.md) | [jvm]<br>abstract fun [getNodes](../-environment/get-nodes.md)(): ListSet<[Node](../-node/index.md)<[T](../-node/index.md)>><br>All the nodes that exist in current environment. |
| [getNodesWithinRange](../-environment/get-nodes-within-range.md) | [jvm]<br>abstract fun [getNodesWithinRange](../-environment/get-nodes-within-range.md)(center: [P](../-incarnation/index.md), range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): ListSet<[Node](../-node/index.md)<[T](../-node/index.md)>><br>Given a [Position](../-position/index.md)(center) this method returns a list of all the surroundings nodes within the given range.<br>[jvm]<br>abstract fun [getNodesWithinRange](../-environment/get-nodes-within-range.md)(center: [Node](../-node/index.md)<[T](../-node/index.md)>, range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): ListSet<[Node](../-node/index.md)<[T](../-node/index.md)>><br>Given a node (center) this method returns a list of all the surroundings nodes within the given range. |
| [getOffset](../-environment/get-offset.md) | [jvm]<br>abstract fun [getOffset](../-environment/get-offset.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)><br>This method allows to know which are the smallest coordinates represented. |
| [getPosition](../-environment/get-position.md) | [jvm]<br>abstract fun [getPosition](../-environment/get-position.md)(node: [Node](../-node/index.md)<[T](../-node/index.md)>): [P](../-incarnation/index.md)<br>Calculates the position of a node. |
| [getSimulation](../-environment/get-simulation.md) | [jvm]<br>abstract fun [getSimulation](../-environment/get-simulation.md)(): [Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.md)<[T](../-node/index.md), [P](../-incarnation/index.md)><br>the current simulation, if present, or throws an [IllegalStateException](https://docs.oracle.com/javase/8/docs/api/java/lang/IllegalStateException.html) otherwise |
| [getSize](../-environment/get-size.md) | [jvm]<br>abstract fun [getSize](../-environment/get-size.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)><br>This method returns the size of the environment as an array of length [getDimensions](../-environment/get-dimensions.md). |
| [getSizeInDistanceUnits](../-environment/get-size-in-distance-units.md) | [jvm]<br>abstract fun [getSizeInDistanceUnits](../-environment/get-size-in-distance-units.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)><br>This method returns the size of the environment as an array of length [getDimensions](../-environment/get-dimensions.md). |
| [isTerminated](../-environment/is-terminated.md) | [jvm]<br>abstract fun [isTerminated](../-environment/is-terminated.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if all the terminators are true |
| [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../-node/index.md)> |
| [makePosition](../-environment/make-position.md) | [jvm]<br>abstract fun [makePosition](../-environment/make-position.md)(coordinates: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)>): [P](../-incarnation/index.md)<br>the coordinates of the point |
| [moveNodeToPosition](../-environment/move-node-to-position.md) | [jvm]<br>abstract fun [moveNodeToPosition](../-environment/move-node-to-position.md)(node: [Node](../-node/index.md)<[T](../-node/index.md)>, position: [P](../-incarnation/index.md))<br>This method moves a node in the environment to some position. |
| [removeNode](../-environment/remove-node.md) | [jvm]<br>abstract fun [removeNode](../-environment/remove-node.md)(node: [Node](../-node/index.md)<[T](../-node/index.md)>)<br>This method allows to remove a node. |
| [setLinkingRule](../-environment/set-linking-rule.md) | [jvm]<br>abstract fun [setLinkingRule](../-environment/set-linking-rule.md)(rule: [LinkingRule](../-linking-rule/index.md)<[T](../-node/index.md), [P](../-incarnation/index.md)>)<br>the rule to set |
| [setSimulation](../-environment/set-simulation.md) | [jvm]<br>abstract fun [setSimulation](../-environment/set-simulation.md)(s: [Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.md)<[T](../-node/index.md), [P](../-incarnation/index.md)>)<br>the simulation |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../-node/index.md)> |

## Inheritors

| Name |
|---|
| [MapEnvironment](../-map-environment/index.md) |

---
title: Environment
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Environment](index.html)



# Environment



[jvm]\
interface [Environment](index.html)<[T](index.html), [P](index.html) : [Position](../-position/index.html)<out [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)<[Node](../-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>> 

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
| [addLayer](add-layer.html) | [jvm]<br>abstract fun [addLayer](add-layer.html)(m: [Molecule](../-molecule/index.html), l: [Layer](../-layer/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>)<br>Add a [Layer](../-layer/index.html) to the [Environment](index.html). |
| [addNode](add-node.html) | [jvm]<br>abstract fun [addNode](add-node.html)(node: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, p: [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html))<br>This method allows to add a new node to this environment. |
| [addTerminator](add-terminator.html) | [jvm]<br>abstract fun [addTerminator](add-terminator.html)(terminator: [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>>)<br>a [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html) indicating whether the simulation should be considered finished |
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getDimensions](get-dimensions.html) | [jvm]<br>abstract fun [getDimensions](get-dimensions.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The number of dimensions of this environment. |
| [getDistanceBetweenNodes](get-distance-between-nodes.html) | [jvm]<br>abstract fun [getDistanceBetweenNodes](get-distance-between-nodes.html)(n1: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, n2: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Measures the distance between two nodes in the environment. |
| [getIncarnation](get-incarnation.html) | [jvm]<br>abstract fun [getIncarnation](get-incarnation.html)(): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Incarnation](../-incarnation/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>><br>the [Incarnation](../-incarnation/index.html) used to initialize the entities of this [Environment](index.html), if it has been set. |
| [getLayer](get-layer.html) | [jvm]<br>abstract fun [getLayer](get-layer.html)(m: [Molecule](../-molecule/index.html)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Layer](../-layer/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>><br>Get the layer associate to the given molecule. |
| [getLayers](get-layers.html) | [jvm]<br>abstract fun [getLayers](get-layers.html)(): ListSet<[Layer](../-layer/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>><br>Return all the Layers in this [Environment](index.html). |
| [getLinkingRule](get-linking-rule.html) | [jvm]<br>abstract fun [getLinkingRule](get-linking-rule.html)(): [LinkingRule](../-linking-rule/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)><br>the current linking rule |
| [getNeighborhood](get-neighborhood.html) | [jvm]<br>abstract fun [getNeighborhood](get-neighborhood.html)(center: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>): [Neighborhood](../-neighborhood/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)><br>Given a node, this method returns its neighborhood. |
| [getNodeByID](get-node-by-i-d.html) | [jvm]<br>abstract fun [getNodeByID](get-node-by-i-d.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Node](../-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)><br>Allows to access a node known its id. |
| [getNodeCount](get-node-count.html) | [jvm]<br>abstract fun [getNodeCount](get-node-count.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the number of nodes currently in the environment |
| [getNodes](get-nodes.html) | [jvm]<br>abstract fun [getNodes](get-nodes.html)(): ListSet<[Node](../-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>><br>All the nodes that exist in current environment. |
| [getNodesWithinRange](get-nodes-within-range.html) | [jvm]<br>abstract fun [getNodesWithinRange](get-nodes-within-range.html)(center: [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html), range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): ListSet<[Node](../-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>><br>Given a [Position](../-position/index.html)(center) this method returns a list of all the surroundings nodes within the given range.<br>[jvm]<br>abstract fun [getNodesWithinRange](get-nodes-within-range.html)(center: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): ListSet<[Node](../-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>><br>Given a node (center) this method returns a list of all the surroundings nodes within the given range. |
| [getOffset](get-offset.html) | [jvm]<br>abstract fun [getOffset](get-offset.html)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)><br>This method allows to know which are the smallest coordinates represented. |
| [getPosition](get-position.html) | [jvm]<br>abstract fun [getPosition](get-position.html)(node: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>): [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)<br>Calculates the position of a node. |
| [getSimulation](get-simulation.html) | [jvm]<br>abstract fun [getSimulation](get-simulation.html)(): [Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)><br>the current simulation, if present, or throws an [IllegalStateException](https://docs.oracle.com/javase/8/docs/api/java/lang/IllegalStateException.html) otherwise |
| [getSize](get-size.html) | [jvm]<br>abstract fun [getSize](get-size.html)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)><br>This method returns the size of the environment as an array of length [getDimensions](get-dimensions.html). |
| [getSizeInDistanceUnits](get-size-in-distance-units.html) | [jvm]<br>abstract fun [getSizeInDistanceUnits](get-size-in-distance-units.html)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)><br>This method returns the size of the environment as an array of length [getDimensions](get-dimensions.html). |
| [isTerminated](is-terminated.html) | [jvm]<br>abstract fun [isTerminated](is-terminated.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if all the terminators are true |
| [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)> |
| [makePosition](make-position.html) | [jvm]<br>abstract fun [makePosition](make-position.html)(coordinates: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)>): [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)<br>the coordinates of the point |
| [moveNodeToPosition](move-node-to-position.html) | [jvm]<br>abstract fun [moveNodeToPosition](move-node-to-position.html)(node: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, position: [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html))<br>This method moves a node in the environment to some position. |
| [removeNode](remove-node.html) | [jvm]<br>abstract fun [removeNode](remove-node.html)(node: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>)<br>This method allows to remove a node. |
| [setLinkingRule](set-linking-rule.html) | [jvm]<br>abstract fun [setLinkingRule](set-linking-rule.html)(rule: [LinkingRule](../-linking-rule/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>)<br>the rule to set |
| [setSimulation](set-simulation.html) | [jvm]<br>abstract fun [setSimulation](set-simulation.html)(s: [Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>)<br>the simulation |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)> |


## Inheritors


| Name |
|---|
| [AbstractEnvironment](../../it.unibo.alchemist.model.implementations.environments/-abstract-environment/index.html) |
| [EnvironmentSupportingDeformableCells](../-environment-supporting-deformable-cells/index.html) |
| [BenchmarkableEnvironment](../-benchmarkable-environment/index.html) |
| [EuclideanEnvironment](../-euclidean-environment/index.html) |


---
title: EnvironmentWithObstacles
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[EnvironmentWithObstacles](index.html)



# EnvironmentWithObstacles



[jvm]\
interface [EnvironmentWithObstacles](index.html)<[W](index.html) : [Obstacle](../-obstacle/index.html)<[P](index.html)>, [T](index.html), [P](index.html) : [Position](../-position/index.html)<[P](index.html)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](index.html)>> : [EuclideanEnvironment](../-euclidean-environment/index.html)<[T](index.html), [P](index.html)> 

An environment with [Obstacle](../-obstacle/index.html)s.



## Parameters


jvm

| | |
|---|---|
| W | the type of obstacles. |
| T | the concentration type. |
| P | the position and vector type for this environment. |



## Functions


| Name | Summary |
|---|---|
| [addLayer](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html#126323689%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [addLayer](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html#126323689%2FFunctions%2F-134779887)(m: [Molecule](../-molecule/index.html), l: [Layer](../-layer/index.html)<[T](index.html), [P](index.html)>) |
| [addNode](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html#-197770120%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [addNode](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html#-197770120%2FFunctions%2F-134779887)(node: [Node](../-node/index.html)<[T](index.html)>, p: [P](index.html)) |
| [addObstacle](add-obstacle.html) | [jvm]<br>abstract fun [addObstacle](add-obstacle.html)(obstacle: [W](index.html))<br>Adds an obstacle to this environment. |
| [addTerminator](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html#-638290442%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [addTerminator](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html#-638290442%2FFunctions%2F-134779887)(terminator: [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](../-environment/index.html)<[T](index.html), [P](index.html)>>) |
| [forEach](../../it.unibo.alchemist.model.implementations.neighborhoods/-simple-neighborhood/index.html#1379299152%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.model.implementations.neighborhoods/-simple-neighborhood/index.html#1379299152%2FFunctions%2F-134779887)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [Node](../-node/index.html)<[T](index.html)>>) |
| [getDimensions](../-environment/get-dimensions.html) | [jvm]<br>abstract fun [getDimensions](../-environment/get-dimensions.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getDistanceBetweenNodes](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html#1545521498%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getDistanceBetweenNodes](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html#1545521498%2FFunctions%2F-134779887)(n1: [Node](../-node/index.html)<[T](index.html)>, n2: [Node](../-node/index.html)<[T](index.html)>): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getIncarnation](../-environment/get-incarnation.html) | [jvm]<br>abstract fun [getIncarnation](../-environment/get-incarnation.html)(): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Incarnation](../-incarnation/index.html)<[T](index.html), [P](index.html)>> |
| [getLayer](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html#-1122345695%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getLayer](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html#-1122345695%2FFunctions%2F-134779887)(m: [Molecule](../-molecule/index.html)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Layer](../-layer/index.html)<[T](index.html), [P](index.html)>> |
| [getLayers](../-environment/get-layers.html) | [jvm]<br>abstract fun [getLayers](../-environment/get-layers.html)(): ListSet<[Layer](../-layer/index.html)<[T](index.html), [P](index.html)>> |
| [getLinkingRule](../-environment/get-linking-rule.html) | [jvm]<br>abstract fun [getLinkingRule](../-environment/get-linking-rule.html)(): [LinkingRule](../-linking-rule/index.html)<[T](index.html), [P](index.html)> |
| [getNeighborhood](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html#-85790470%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getNeighborhood](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html#-85790470%2FFunctions%2F-134779887)(center: [Node](../-node/index.html)<[T](index.html)>): [Neighborhood](../-neighborhood/index.html)<[T](index.html)> |
| [getNodeByID](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html#-133466387%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getNodeByID](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html#-133466387%2FFunctions%2F-134779887)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Node](../-node/index.html)<[T](index.html)> |
| [getNodeCount](../-environment/get-node-count.html) | [jvm]<br>abstract fun [getNodeCount](../-environment/get-node-count.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getNodes](../-environment/get-nodes.html) | [jvm]<br>abstract fun [getNodes](../-environment/get-nodes.html)(): ListSet<[Node](../-node/index.html)<[T](index.html)>> |
| [getNodesWithinRange](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html#634323809%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getNodesWithinRange](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html#634323809%2FFunctions%2F-134779887)(center: [P](index.html), range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): ListSet<[Node](../-node/index.html)<[T](index.html)>><br>abstract fun [getNodesWithinRange](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html#-1612566862%2FFunctions%2F-134779887)(center: [Node](../-node/index.html)<[T](index.html)>, range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): ListSet<[Node](../-node/index.html)<[T](index.html)>> |
| [getOffset](../-environment/get-offset.html) | [jvm]<br>abstract fun [getOffset](../-environment/get-offset.html)(): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html) |
| [getPosition](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html#1369612629%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getPosition](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html#1369612629%2FFunctions%2F-134779887)(node: [Node](../-node/index.html)<[T](index.html)>): [P](index.html) |
| [getSimulation](../-environment/get-simulation.html) | [jvm]<br>abstract fun [getSimulation](../-environment/get-simulation.html)(): [Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.html)<[T](index.html), [P](index.html)> |
| [getSize](../-environment/get-size.html) | [jvm]<br>abstract fun [getSize](../-environment/get-size.html)(): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html) |
| [getSizeInDistanceUnits](../-environment/get-size-in-distance-units.html) | [jvm]<br>abstract fun [getSizeInDistanceUnits](../-environment/get-size-in-distance-units.html)(): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html) |
| [intersectsObstacle](intersects-obstacle.html) | [jvm]<br>abstract fun [intersectsObstacle](intersects-obstacle.html)(start: [P](index.html), end: [P](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks whether there is at least an obstacle intersecting the line connecting [start](intersects-obstacle.html) and [end](intersects-obstacle.html). |
| [isTerminated](../-environment/is-terminated.html) | [jvm]<br>abstract fun [isTerminated](../-environment/is-terminated.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [iterator](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#-1651023311%2FFunctions%2F-134779887) | [jvm]<br>abstract operator override fun [iterator](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html#-1651023311%2FFunctions%2F-134779887)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[Node](../-node/index.html)<[T](index.html)>> |
| [makePosition](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html#1042884226%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [makePosition](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html#1042884226%2FFunctions%2F-134779887)(vararg coordinates: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)): [P](index.html)<br>[jvm]<br>abstract fun [makePosition](../-euclidean-environment/make-position.html)(vararg coordinates: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](index.html)<br>Creates a [Position](../-position/index.html) compatible with this environment given its [coordinates](../-euclidean-environment/make-position.html). |
| [moveNode](../-euclidean-environment/move-node.html) | [jvm]<br>open fun [moveNode](../-euclidean-environment/move-node.html)(node: [Node](../-node/index.html)<[T](index.html)>, direction: [P](index.html))<br>This method moves a [node](../-euclidean-environment/move-node.html) in the environment toward some [direction](../-euclidean-environment/move-node.html). |
| [moveNodeToPosition](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html#-302891260%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [moveNodeToPosition](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html#-302891260%2FFunctions%2F-134779887)(node: [Node](../-node/index.html)<[T](index.html)>, position: [P](index.html)) |
| [next](next.html) | [jvm]<br>abstract fun [next](next.html)(current: [P](index.html), desired: [P](index.html)): [P](index.html)<br>This method must calculate the ABSOLUTE next allowed position given the current position and the position in which the node wants to move. |
| [removeNode](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html#-306697004%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [removeNode](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html#-306697004%2FFunctions%2F-134779887)(node: [Node](../-node/index.html)<[T](index.html)>) |
| [removeObstacle](remove-obstacle.html) | [jvm]<br>abstract fun [removeObstacle](remove-obstacle.html)(obstacle: [W](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Removes an obstacle from this environment. |
| [setLinkingRule](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html#-1005317528%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [setLinkingRule](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html#-1005317528%2FFunctions%2F-134779887)(rule: [LinkingRule](../-linking-rule/index.html)<[T](index.html), [P](index.html)>) |
| [setSimulation](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html#1147788016%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [setSimulation](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.html#1147788016%2FFunctions%2F-134779887)(s: [Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.html)<[T](index.html), [P](index.html)>) |
| [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.html#-1387152138%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.html#-1387152138%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Node](../-node/index.html)<[T](index.html)>> |


## Properties


| Name | Summary |
|---|---|
| [obstacles](obstacles.html) | [jvm]<br>abstract val [obstacles](obstacles.html): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[W](index.html)><br>A list of all the obstacles in this environment. |
| [origin](index.html#-939172749%2FProperties%2F-134779887) | [jvm]<br>open val [origin](index.html#-939172749%2FProperties%2F-134779887): [P](index.html)<br>Create a position corresponding to the origin of this environment. |


## Inheritors


| Name |
|---|
| [Environment2DWithObstacles](../../it.unibo.alchemist.model.interfaces.environments/-environment2-d-with-obstacles/index.html) |
| [EnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-environment-with-graph/index.html) |


//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[EnvironmentWithObstacles](index.md)

# EnvironmentWithObstacles

[jvm]\
interface [EnvironmentWithObstacles](index.md)<[W](index.md) : [Obstacle](../-obstacle/index.md)<[P](index.md)>, [T](index.md), [P](index.md) : [Position](../-position/index.md)<[P](index.md)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](index.md)>> : [EuclideanEnvironment](../-euclidean-environment/index.md)<[T](index.md), [P](index.md)> 

An environment with [Obstacle](../-obstacle/index.md)s.

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
| [addLayer](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#126323689%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [addLayer](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#126323689%2FFunctions%2F-267951372)(m: [Molecule](../-molecule/index.md), l: [Layer](../-layer/index.md)<[T](index.md), [P](index.md)>) |
| [addNode](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#-197770120%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [addNode](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#-197770120%2FFunctions%2F-267951372)(node: [Node](../-node/index.md)<[T](index.md)>, p: [P](index.md)) |
| [addObstacle](add-obstacle.md) | [jvm]<br>abstract fun [addObstacle](add-obstacle.md)(obstacle: [W](index.md))<br>Adds an obstacle to this environment. |
| [addTerminator](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#-638290442%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [addTerminator](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#-638290442%2FFunctions%2F-267951372)(terminator: [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](../-environment/index.md)<[T](index.md), [P](index.md)>>) |
| [forEach](../../it.unibo.alchemist.model.implementations.neighborhoods/-simple-neighborhood/index.md#1379299152%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.model.implementations.neighborhoods/-simple-neighborhood/index.md#1379299152%2FFunctions%2F-267951372)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [Node](../-node/index.md)<[T](index.md)>>) |
| [getDimensions](../-environment/get-dimensions.md) | [jvm]<br>abstract fun [getDimensions](../-environment/get-dimensions.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getDistanceBetweenNodes](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#1545521498%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getDistanceBetweenNodes](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#1545521498%2FFunctions%2F-267951372)(n1: [Node](../-node/index.md)<[T](index.md)>, n2: [Node](../-node/index.md)<[T](index.md)>): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getIncarnation](../-environment/get-incarnation.md) | [jvm]<br>abstract fun [getIncarnation](../-environment/get-incarnation.md)(): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Incarnation](../-incarnation/index.md)<[T](index.md), [P](index.md)>> |
| [getLayer](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#-1122345695%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getLayer](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#-1122345695%2FFunctions%2F-267951372)(m: [Molecule](../-molecule/index.md)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Layer](../-layer/index.md)<[T](index.md), [P](index.md)>> |
| [getLayers](../-environment/get-layers.md) | [jvm]<br>abstract fun [getLayers](../-environment/get-layers.md)(): ListSet<[Layer](../-layer/index.md)<[T](index.md), [P](index.md)>> |
| [getLinkingRule](../-environment/get-linking-rule.md) | [jvm]<br>abstract fun [getLinkingRule](../-environment/get-linking-rule.md)(): [LinkingRule](../-linking-rule/index.md)<[T](index.md), [P](index.md)> |
| [getNeighborhood](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#-85790470%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getNeighborhood](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#-85790470%2FFunctions%2F-267951372)(center: [Node](../-node/index.md)<[T](index.md)>): [Neighborhood](../-neighborhood/index.md)<[T](index.md)> |
| [getNodeByID](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#-133466387%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getNodeByID](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#-133466387%2FFunctions%2F-267951372)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Node](../-node/index.md)<[T](index.md)> |
| [getNodeCount](../-environment/get-node-count.md) | [jvm]<br>abstract fun [getNodeCount](../-environment/get-node-count.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getNodes](../-environment/get-nodes.md) | [jvm]<br>abstract fun [getNodes](../-environment/get-nodes.md)(): ListSet<[Node](../-node/index.md)<[T](index.md)>> |
| [getNodesWithinRange](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#634323809%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getNodesWithinRange](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#634323809%2FFunctions%2F-267951372)(center: [P](index.md), range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): ListSet<[Node](../-node/index.md)<[T](index.md)>><br>abstract fun [getNodesWithinRange](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#-1612566862%2FFunctions%2F-267951372)(center: [Node](../-node/index.md)<[T](index.md)>, range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): ListSet<[Node](../-node/index.md)<[T](index.md)>> |
| [getOffset](../-environment/get-offset.md) | [jvm]<br>abstract fun [getOffset](../-environment/get-offset.md)(): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html) |
| [getPosition](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#1369612629%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getPosition](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#1369612629%2FFunctions%2F-267951372)(node: [Node](../-node/index.md)<[T](index.md)>): [P](index.md) |
| [getSimulation](../-environment/get-simulation.md) | [jvm]<br>abstract fun [getSimulation](../-environment/get-simulation.md)(): [Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.md)<[T](index.md), [P](index.md)> |
| [getSize](../-environment/get-size.md) | [jvm]<br>abstract fun [getSize](../-environment/get-size.md)(): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html) |
| [getSizeInDistanceUnits](../-environment/get-size-in-distance-units.md) | [jvm]<br>abstract fun [getSizeInDistanceUnits](../-environment/get-size-in-distance-units.md)(): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html) |
| [intersectsObstacle](intersects-obstacle.md) | [jvm]<br>abstract fun [intersectsObstacle](intersects-obstacle.md)(start: [P](index.md), end: [P](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks whether there is at least an obstacle intersecting the line connecting [start](intersects-obstacle.md) and [end](intersects-obstacle.md). |
| [isTerminated](../-environment/is-terminated.md) | [jvm]<br>abstract fun [isTerminated](../-environment/is-terminated.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [iterator](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#-1651023311%2FFunctions%2F-267951372) | [jvm]<br>abstract operator override fun [iterator](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#-1651023311%2FFunctions%2F-267951372)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[Node](../-node/index.md)<[T](index.md)>> |
| [makePosition](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#1042884226%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [makePosition](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#1042884226%2FFunctions%2F-267951372)(vararg coordinates: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)): [P](index.md)<br>[jvm]<br>abstract fun [makePosition](../-euclidean-environment/make-position.md)(vararg coordinates: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](index.md)<br>Creates a [Position](../-position/index.md) compatible with this environment given its [coordinates](../-euclidean-environment/make-position.md). |
| [moveNode](../-euclidean-environment/move-node.md) | [jvm]<br>open fun [moveNode](../-euclidean-environment/move-node.md)(node: [Node](../-node/index.md)<[T](index.md)>, direction: [P](index.md))<br>This method moves a [node](../-euclidean-environment/move-node.md) in the environment toward some [direction](../-euclidean-environment/move-node.md). |
| [moveNodeToPosition](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#-302891260%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [moveNodeToPosition](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#-302891260%2FFunctions%2F-267951372)(node: [Node](../-node/index.md)<[T](index.md)>, position: [P](index.md)) |
| [next](next.md) | [jvm]<br>abstract fun [next](next.md)(current: [P](index.md), desired: [P](index.md)): [P](index.md)<br>This method must calculate the ABSOLUTE next allowed position given the current position and the position in which the node wants to move. |
| [removeNode](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#-306697004%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [removeNode](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#-306697004%2FFunctions%2F-267951372)(node: [Node](../-node/index.md)<[T](index.md)>) |
| [removeObstacle](remove-obstacle.md) | [jvm]<br>abstract fun [removeObstacle](remove-obstacle.md)(obstacle: [W](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Removes an obstacle from this environment. |
| [setLinkingRule](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#-1005317528%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [setLinkingRule](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#-1005317528%2FFunctions%2F-267951372)(rule: [LinkingRule](../-linking-rule/index.md)<[T](index.md), [P](index.md)>) |
| [setSimulation](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#1147788016%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [setSimulation](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#1147788016%2FFunctions%2F-267951372)(s: [Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.md)<[T](index.md), [P](index.md)>) |
| [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Node](../-node/index.md)<[T](index.md)>> |

## Properties

| Name | Summary |
|---|---|
| [obstacles](obstacles.md) | [jvm]<br>abstract val [obstacles](obstacles.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[W](index.md)><br>A list of all the obstacles in this environment. |
| [origin](index.md#-939172749%2FProperties%2F-267951372) | [jvm]<br>open val [origin](index.md#-939172749%2FProperties%2F-267951372): [P](index.md)<br>Create a position corresponding to the origin of this environment. |

## Inheritors

| Name |
|---|
| [Environment2DWithObstacles](../../it.unibo.alchemist.model.interfaces.environments/-environment2-d-with-obstacles/index.md) |
| [EnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-environment-with-graph/index.md) |

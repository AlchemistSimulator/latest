//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.environments](../index.md)/[Continuous2DEnvironment](index.md)

# Continuous2DEnvironment

[jvm]\
open class [Continuous2DEnvironment](index.md)<[T](index.md)>(**incarnation**: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>) : [Abstract2DEnvironment](../-abstract2-d-environment/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)> , [Euclidean2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment/index.md)<[T](index.md)> , [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md)<[T](index.md)> 

Implementation of [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md).

## Constructors

| | |
|---|---|
| [Continuous2DEnvironment](-continuous2-d-environment.md) | [jvm]<br>fun <[T](index.md)> [Continuous2DEnvironment](-continuous2-d-environment.md)(incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [jvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [addLayer](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md#806138134%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [addLayer](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md#806138134%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), p1: [Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>) |
| [addNode](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md#1375163507%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [addNode](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md#1375163507%2FFunctions%2F-267951372)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, p1: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)) |
| [addTerminator](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md#672173749%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [addTerminator](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md#672173749%2FFunctions%2F-267951372)(p0: [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>>) |
| [computeActualInsertionPosition](../-image-environment-with-graph/index.md#1288282826%2FFunctions%2F-267951372) | [jvm]<br>open override fun [computeActualInsertionPosition](../-image-environment-with-graph/index.md#1288282826%2FFunctions%2F-267951372)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, p1: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md) |
| [farthestPositionReachable](farthest-position-reachable.md) | [jvm]<br>open override fun [farthestPositionReachable](farthest-position-reachable.md)(node: [NodeWithShape](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md)<[T](index.md), *, *>, desiredPosition: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), hitboxRadius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)<br>[node](farthest-position-reachable.md). |
| [forEach](../../it.unibo.alchemist.model.implementations.neighborhoods/-simple-neighborhood/index.md#1379299152%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.model.implementations.neighborhoods/-simple-neighborhood/index.md#1379299152%2FFunctions%2F-267951372)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>>) |
| [getDimensions](../../it.unibo.alchemist.model.interfaces/-environment/get-dimensions.md) | [jvm]<br>abstract fun [getDimensions](../../it.unibo.alchemist.model.interfaces/-environment/get-dimensions.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getDistanceBetweenNodes](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#1545521498%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getDistanceBetweenNodes](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#1545521498%2FFunctions%2F-267951372)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, p1: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getHeading](get-heading.md) | [jvm]<br>open override fun [getHeading](get-heading.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)<br>Gets the heading of a node as a direction vector. |
| [getIncarnation](../../it.unibo.alchemist.model.interfaces/-environment/get-incarnation.md) | [jvm]<br>abstract fun [getIncarnation](../../it.unibo.alchemist.model.interfaces/-environment/get-incarnation.md)(): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>> |
| [getLayer](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#-1122345695%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getLayer](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#-1122345695%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>> |
| [getLayers](../../it.unibo.alchemist.model.interfaces/-environment/get-layers.md) | [jvm]<br>abstract fun [getLayers](../../it.unibo.alchemist.model.interfaces/-environment/get-layers.md)(): ListSet<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>> |
| [getLinkingRule](../../it.unibo.alchemist.model.interfaces/-environment/get-linking-rule.md) | [jvm]<br>abstract fun [getLinkingRule](../../it.unibo.alchemist.model.interfaces/-environment/get-linking-rule.md)(): [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)> |
| [getNeighborhood](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#-85790470%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getNeighborhood](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#-85790470%2FFunctions%2F-267951372)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.md)<[T](index.md)> |
| [getNodeByID](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#-133466387%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getNodeByID](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#-133466387%2FFunctions%2F-267951372)(p0: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)> |
| [getNodeCount](../../it.unibo.alchemist.model.interfaces/-environment/get-node-count.md) | [jvm]<br>abstract fun [getNodeCount](../../it.unibo.alchemist.model.interfaces/-environment/get-node-count.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getNodes](../../it.unibo.alchemist.model.interfaces/-environment/get-nodes.md) | [jvm]<br>abstract fun [getNodes](../../it.unibo.alchemist.model.interfaces/-environment/get-nodes.md)(): ListSet<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>> |
| [getNodesWithin](get-nodes-within.md) | [jvm]<br>open override fun [getNodesWithin](get-nodes-within.md)(shape: [Euclidean2DShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.md#1496739300%2FClasslikes%2F-267951372)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>><br>Gets all nodes whose shape.intersect is true for the given shape. |
| [getNodesWithinRange](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md#1286723092%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getNodesWithinRange](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md#1286723092%2FFunctions%2F-267951372)(p0: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), p1: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): ListSet<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>><br>abstract fun [getNodesWithinRange](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#-1612566862%2FFunctions%2F-267951372)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, p1: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): ListSet<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>> |
| [getOffset](../../it.unibo.alchemist.model.interfaces/-environment/get-offset.md) | [jvm]<br>abstract fun [getOffset](../../it.unibo.alchemist.model.interfaces/-environment/get-offset.md)(): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html) |
| [getPosition](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#1369612629%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getPosition](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#1369612629%2FFunctions%2F-267951372)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md) |
| [getShape](get-shape.md) | [jvm]<br>open override fun [getShape](get-shape.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>): [Euclidean2DShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.md#1496739300%2FClasslikes%2F-267951372)<br>Gets the shape of a node relatively to its position and heading in the environment. |
| [getSimulation](../../it.unibo.alchemist.model.interfaces/-environment/get-simulation.md) | [jvm]<br>abstract fun [getSimulation](../../it.unibo.alchemist.model.interfaces/-environment/get-simulation.md)(): [Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)> |
| [getSize](../../it.unibo.alchemist.model.interfaces/-environment/get-size.md) | [jvm]<br>abstract fun [getSize](../../it.unibo.alchemist.model.interfaces/-environment/get-size.md)(): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html) |
| [getSizeInDistanceUnits](../../it.unibo.alchemist.model.interfaces/-environment/get-size-in-distance-units.md) | [jvm]<br>abstract fun [getSizeInDistanceUnits](../../it.unibo.alchemist.model.interfaces/-environment/get-size-in-distance-units.md)(): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html) |
| [ifEngineAvailable](../-image-environment-with-graph/index.md#1013445205%2FFunctions%2F-267951372) | [jvm]<br>fun [ifEngineAvailable](../-image-environment-with-graph/index.md#1013445205%2FFunctions%2F-267951372)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<[Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>>) |
| [includeObject](../-image-environment-with-graph/index.md#-1824171008%2FFunctions%2F-267951372) | [jvm]<br>fun [includeObject](../-image-environment-with-graph/index.md#-1824171008%2FFunctions%2F-267951372)(p0: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md))<br>fun [includeObject](../-image-environment-with-graph/index.md#-1722409184%2FFunctions%2F-267951372)(p0: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), p1: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), p2: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), p3: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [isTerminated](../../it.unibo.alchemist.model.interfaces/-environment/is-terminated.md) | [jvm]<br>abstract fun [isTerminated](../../it.unibo.alchemist.model.interfaces/-environment/is-terminated.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [iterator](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#-1651023311%2FFunctions%2F-267951372) | [jvm]<br>abstract operator override fun [iterator](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#-1651023311%2FFunctions%2F-267951372)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>> |
| [makePosition](make-position.md) | [jvm]<br>open override fun [makePosition](make-position.md)(vararg coordinates: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)<br>Creates an euclidean position from the given coordinates.<br>[jvm]<br>open override fun [makePosition](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment/make-position.md)(vararg coordinates: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)<br>open fun [makePosition](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment/make-position.md)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)<br>Creates a new [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md). |
| [moveNode](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md#1726629773%2FFunctions%2F-267951372) | [jvm]<br>open fun [moveNode](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md#1726629773%2FFunctions%2F-267951372)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, direction: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)) |
| [moveNodeToPosition](move-node-to-position.md) | [jvm]<br>open override fun [moveNodeToPosition](move-node-to-position.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, newpos: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md))<br>Moves the [node](move-node-to-position.md) to the [farthestPositionReachable](farthest-position-reachable.md) towards the desired [newpos](move-node-to-position.md). |
| [removeNode](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#-306697004%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [removeNode](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment-with-graph/index.md#-306697004%2FFunctions%2F-267951372)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>) |
| [setHeading](set-heading.md) | [jvm]<br>open override fun [setHeading](set-heading.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, direction: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md))<br>Sets the heading of a node. |
| [setLinkingRule](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md#73596215%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [setLinkingRule](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md#73596215%2FFunctions%2F-267951372)(p0: [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>) |
| [setPosition](../-image-environment-with-graph/index.md#1073399482%2FFunctions%2F-267951372) | [jvm]<br>fun [setPosition](../-image-environment-with-graph/index.md#1073399482%2FFunctions%2F-267951372)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, p1: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)) |
| [setSimulation](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md#709873583%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [setSimulation](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md#709873583%2FFunctions%2F-267951372)(p0: [Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>) |
| [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>> |
| [updateNeighborhood](../-image-environment-with-graph/index.md#414729712%2FFunctions%2F-267951372) | [jvm]<br>fun [updateNeighborhood](../-image-environment-with-graph/index.md#414729712%2FFunctions%2F-267951372)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, p1: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [origin](index.md#-1543060979%2FProperties%2F-267951372) | [jvm]<br>open override val [origin](index.md#-1543060979%2FProperties%2F-267951372): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md) |
| [shapeFactory](shape-factory.md) | [jvm]<br>open override val [shapeFactory](shape-factory.md): [Euclidean2DShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-shape-factory/index.md)<br>A factory of shapes compatible with this environment. |

## Inheritors

| Name |
|---|
| [MuseumHall](../-museum-hall/index.md) |
| [LimitedContinuos2D](../-limited-continuos2-d/index.md) |
//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces.environments](../index.md)/[PhysicsEnvironmentWithGraph](index.md)

# PhysicsEnvironmentWithGraph

[jvm]\
interface [PhysicsEnvironmentWithGraph](index.md)<[W](index.md) : [Obstacle](../../it.unibo.alchemist.model.interfaces/-obstacle/index.md)<[P](index.md)>, [T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[P](index.md)>, [N](index.md) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.md)<[P](index.md), [A](index.md)>, [E](index.md), [F](index.md) : [GeometricShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/index.md)<[P](index.md), [A](index.md)>> : [EnvironmentWithGraph](../-environment-with-graph/index.md)<[W](index.md), [T](index.md), [P](index.md), [A](index.md), [N](index.md), [E](index.md)> , [PhysicsEnvironment](../-physics-environment/index.md)<[T](index.md), [P](index.md), [A](index.md), [F](index.md)> 

An [EnvironmentWithGraph](../-environment-with-graph/index.md) supporting physics.

## Functions

| Name | Summary |
|---|---|
| [addLayer](index.md#126323689%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [addLayer](index.md#126323689%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), p1: [Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.md)<[T](index.md), [P](index.md)>) |
| [addNode](index.md#-197770120%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [addNode](index.md#-197770120%2FFunctions%2F-267951372)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, p1: [P](index.md)) |
| [addObstacle](../../it.unibo.alchemist.model.interfaces/-environment-with-obstacles/add-obstacle.md) | [jvm]<br>abstract fun [addObstacle](../../it.unibo.alchemist.model.interfaces/-environment-with-obstacles/add-obstacle.md)(obstacle: [W](index.md)) |
| [addTerminator](index.md#-638290442%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [addTerminator](index.md#-638290442%2FFunctions%2F-267951372)(p0: [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [P](index.md)>>) |
| [farthestPositionReachable](../-physics-environment/farthest-position-reachable.md) | [jvm]<br>abstract fun [farthestPositionReachable](../-physics-environment/farthest-position-reachable.md)(node: [NodeWithShape](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md)<[T](index.md), *, *>, desiredPosition: [P](index.md), hitboxRadius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = node.shape.radius): [P](index.md)<br>Computes the farthest position reachable by a [node](../-physics-environment/farthest-position-reachable.md) towards a [desiredPosition](../-physics-environment/farthest-position-reachable.md), avoiding node overlapping. |
| [forEach](../../it.unibo.alchemist.model.implementations.neighborhoods/-simple-neighborhood/index.md#1379299152%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.model.implementations.neighborhoods/-simple-neighborhood/index.md#1379299152%2FFunctions%2F-267951372)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>>) |
| [getDimensions](../../it.unibo.alchemist.model.interfaces/-environment/get-dimensions.md) | [jvm]<br>abstract fun [getDimensions](../../it.unibo.alchemist.model.interfaces/-environment/get-dimensions.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getDistanceBetweenNodes](index.md#1545521498%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getDistanceBetweenNodes](index.md#1545521498%2FFunctions%2F-267951372)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, p1: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getHeading](../-physics-environment/get-heading.md) | [jvm]<br>abstract fun [getHeading](../-physics-environment/get-heading.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>): [P](index.md)<br>Gets the heading of a node as a direction vector. |
| [getIncarnation](../../it.unibo.alchemist.model.interfaces/-environment/get-incarnation.md) | [jvm]<br>abstract fun [getIncarnation](../../it.unibo.alchemist.model.interfaces/-environment/get-incarnation.md)(): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.md)<[T](index.md), [P](index.md)>> |
| [getLayer](index.md#-1122345695%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getLayer](index.md#-1122345695%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.md)<[T](index.md), [P](index.md)>> |
| [getLayers](../../it.unibo.alchemist.model.interfaces/-environment/get-layers.md) | [jvm]<br>abstract fun [getLayers](../../it.unibo.alchemist.model.interfaces/-environment/get-layers.md)(): ListSet<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.md)<[T](index.md), [P](index.md)>> |
| [getLinkingRule](../../it.unibo.alchemist.model.interfaces/-environment/get-linking-rule.md) | [jvm]<br>abstract fun [getLinkingRule](../../it.unibo.alchemist.model.interfaces/-environment/get-linking-rule.md)(): [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.md)<[T](index.md), [P](index.md)> |
| [getNeighborhood](index.md#-85790470%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getNeighborhood](index.md#-85790470%2FFunctions%2F-267951372)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.md)<[T](index.md)> |
| [getNodeByID](index.md#-133466387%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getNodeByID](index.md#-133466387%2FFunctions%2F-267951372)(p0: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)> |
| [getNodeCount](../../it.unibo.alchemist.model.interfaces/-environment/get-node-count.md) | [jvm]<br>abstract fun [getNodeCount](../../it.unibo.alchemist.model.interfaces/-environment/get-node-count.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getNodes](../../it.unibo.alchemist.model.interfaces/-environment/get-nodes.md) | [jvm]<br>abstract fun [getNodes](../../it.unibo.alchemist.model.interfaces/-environment/get-nodes.md)(): ListSet<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>> |
| [getNodesWithin](../-physics-environment/get-nodes-within.md) | [jvm]<br>abstract fun [getNodesWithin](../-physics-environment/get-nodes-within.md)(shape: [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.md)<[P](index.md), [A](index.md)>): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>><br>Gets all nodes whose shape.intersect is true for the given shape. |
| [getNodesWithinRange](index.md#634323809%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getNodesWithinRange](index.md#634323809%2FFunctions%2F-267951372)(p0: [P](index.md), p1: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): ListSet<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>><br>abstract fun [getNodesWithinRange](index.md#-1612566862%2FFunctions%2F-267951372)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, p1: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): ListSet<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>> |
| [getOffset](../../it.unibo.alchemist.model.interfaces/-environment/get-offset.md) | [jvm]<br>abstract fun [getOffset](../../it.unibo.alchemist.model.interfaces/-environment/get-offset.md)(): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html) |
| [getPosition](index.md#1369612629%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getPosition](index.md#1369612629%2FFunctions%2F-267951372)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>): [P](index.md) |
| [getShape](../-physics-environment/get-shape.md) | [jvm]<br>abstract fun [getShape](../-physics-environment/get-shape.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.md)<[P](index.md), [A](index.md)><br>Gets the shape of a node relatively to its position and heading in the environment. |
| [getSimulation](../../it.unibo.alchemist.model.interfaces/-environment/get-simulation.md) | [jvm]<br>abstract fun [getSimulation](../../it.unibo.alchemist.model.interfaces/-environment/get-simulation.md)(): [Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.md)<[T](index.md), [P](index.md)> |
| [getSize](../../it.unibo.alchemist.model.interfaces/-environment/get-size.md) | [jvm]<br>abstract fun [getSize](../../it.unibo.alchemist.model.interfaces/-environment/get-size.md)(): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html) |
| [getSizeInDistanceUnits](../../it.unibo.alchemist.model.interfaces/-environment/get-size-in-distance-units.md) | [jvm]<br>abstract fun [getSizeInDistanceUnits](../../it.unibo.alchemist.model.interfaces/-environment/get-size-in-distance-units.md)(): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html) |
| [intersectsObstacle](../../it.unibo.alchemist.model.interfaces/-environment-with-obstacles/intersects-obstacle.md) | [jvm]<br>abstract fun [intersectsObstacle](../../it.unibo.alchemist.model.interfaces/-environment-with-obstacles/intersects-obstacle.md)(start: [P](index.md), end: [P](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isTerminated](../../it.unibo.alchemist.model.interfaces/-environment/is-terminated.md) | [jvm]<br>abstract fun [isTerminated](../../it.unibo.alchemist.model.interfaces/-environment/is-terminated.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [iterator](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#-1651023311%2FFunctions%2F-267951372) | [jvm]<br>abstract operator override fun [iterator](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#-1651023311%2FFunctions%2F-267951372)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>> |
| [makePosition](index.md#1042884226%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [makePosition](index.md#1042884226%2FFunctions%2F-267951372)(vararg p0: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)): [P](index.md)<br>abstract fun [makePosition](../../it.unibo.alchemist.model.interfaces/-euclidean-environment/make-position.md)(vararg coordinates: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [P](index.md) |
| [moveNode](../../it.unibo.alchemist.model.interfaces/-euclidean-environment/move-node.md) | [jvm]<br>open fun [moveNode](../../it.unibo.alchemist.model.interfaces/-euclidean-environment/move-node.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, direction: [P](index.md)) |
| [moveNodeToPosition](index.md#-302891260%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [moveNodeToPosition](index.md#-302891260%2FFunctions%2F-267951372)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, p1: [P](index.md)) |
| [next](../../it.unibo.alchemist.model.interfaces/-environment-with-obstacles/next.md) | [jvm]<br>abstract fun [next](../../it.unibo.alchemist.model.interfaces/-environment-with-obstacles/next.md)(current: [P](index.md), desired: [P](index.md)): [P](index.md) |
| [removeNode](index.md#-306697004%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [removeNode](index.md#-306697004%2FFunctions%2F-267951372)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>) |
| [removeObstacle](../../it.unibo.alchemist.model.interfaces/-environment-with-obstacles/remove-obstacle.md) | [jvm]<br>abstract fun [removeObstacle](../../it.unibo.alchemist.model.interfaces/-environment-with-obstacles/remove-obstacle.md)(obstacle: [W](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [setHeading](../-physics-environment/set-heading.md) | [jvm]<br>abstract fun [setHeading](../-physics-environment/set-heading.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, direction: [P](index.md))<br>Sets the heading of a node. |
| [setLinkingRule](index.md#-1005317528%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [setLinkingRule](index.md#-1005317528%2FFunctions%2F-267951372)(p0: [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.md)<[T](index.md), [P](index.md)>) |
| [setSimulation](index.md#1147788016%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [setSimulation](index.md#1147788016%2FFunctions%2F-267951372)(p0: [Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.md)<[T](index.md), [P](index.md)>) |
| [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>> |

## Properties

| Name | Summary |
|---|---|
| [graph](index.md#682165138%2FProperties%2F-267951372) | [jvm]<br>abstract val [graph](index.md#682165138%2FProperties%2F-267951372): [NavigationGraph](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-navigation-graph/index.md)<[P](index.md), [A](index.md), [N](index.md), [E](index.md)><br>The navigation graph. |
| [obstacles](index.md#-1877160868%2FProperties%2F-267951372) | [jvm]<br>abstract val [obstacles](index.md#-1877160868%2FProperties%2F-267951372): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[W](index.md)> |
| [origin](index.md#-196007340%2FProperties%2F-267951372) | [jvm]<br>open val [origin](index.md#-196007340%2FProperties%2F-267951372): [P](index.md) |
| [shapeFactory](index.md#1486450417%2FProperties%2F-267951372) | [jvm]<br>abstract val [shapeFactory](index.md#1486450417%2FProperties%2F-267951372): [F](index.md)<br>A factory of shapes compatible with this environment. |

## Inheritors

| Name |
|---|
| [EuclideanPhysics2DEnvironmentWithGraph](../-euclidean-physics2-d-environment-with-graph/index.md) |
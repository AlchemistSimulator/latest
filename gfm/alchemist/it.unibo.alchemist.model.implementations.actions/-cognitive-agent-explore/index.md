//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[CognitiveAgentExplore](index.md)

# CognitiveAgentExplore

[jvm]\
class [CognitiveAgentExplore](index.md)<[T](index.md), [L](index.md) : [Euclidean2DConvexShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.md#-786369621%2FClasslikes%2F-267951372), [R](index.md)>(**environment**: [Euclidean2DEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment-with-graph/index.md)<*, [T](index.md), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.md)>, **reaction**: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>, **pedestrian**: [OrientingPedestrian2D](../../it.unibo.alchemist.model.interfaces/index.md#1465026919%2FClasslikes%2F-267951372)<[T](index.md), [L](index.md), [R](index.md)>) : [CognitiveAgentNavigationAction2D](../-cognitive-agent-navigation-action2-d/index.md)<[T](index.md), [L](index.md), [R](index.md)> 

A [NavigationAction](../../it.unibo.alchemist.model.interfaces/-navigation-action/index.md) using [Exploring](../../it.unibo.alchemist.model.implementations.actions.navigationstrategies/-exploring/index.md) navigation strategy.

## Parameters

jvm

| | |
|---|---|
| T | the concentration type. |
| L | the type of landmarks of the pedestrian's cognitive map. |
| R | the type of edges of the pedestrian's cognitive map, representing the [R](index.md)elations between landmarks. |

## Constructors

| | |
|---|---|
| [CognitiveAgentExplore](-cognitive-agent-explore.md) | [jvm]<br>fun <[T](index.md)> [CognitiveAgentExplore](-cognitive-agent-explore.md)(environment: [Euclidean2DEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment-with-graph/index.md)<*, [T](index.md), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>, pedestrian: [OrientingPedestrian2D](../../it.unibo.alchemist.model.interfaces/index.md#1465026919%2FClasslikes%2F-267951372)<[T](index.md), [L](index.md), [R](index.md)>)<br>the concentration type. |

## Functions

| Name | Summary |
|---|---|
| [cloneAction](../-abstract-steering-action/clone-action.md) | [jvm]<br>open override fun [cloneAction](../-abstract-steering-action/clone-action.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.md)<[T](index.md)> |
| [crossDoor](../-cognitive-agent-navigation-action2-d/cross-door.md) | [jvm]<br>open override fun [crossDoor](../-cognitive-agent-navigation-action2-d/cross-door.md)(door: [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.md))<br>Moves the pedestrian across the provided [door](../-cognitive-agent-navigation-action2-d/cross-door.md), which must be among doorsInSight. |
| [declareDependencyTo](../-camera-see/index.md#1970369254%2FFunctions%2F-267951372) | [jvm]<br>fun [declareDependencyTo](../-camera-see/index.md#1970369254%2FFunctions%2F-267951372)(p0: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)) |
| [doorsInSight](../-abstract-navigation-action/doors-in-sight.md) | [jvm]<br>open override fun [doorsInSight](../-abstract-navigation-action/doors-in-sight.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.md)> |
| [execute](../-abstract-move-node/execute.md) | [jvm]<br>open override fun [execute](../-abstract-move-node/execute.md)() |
| [getConcentration](../-camera-see/index.md#-1328510210%2FFunctions%2F-267951372) | [jvm]<br>fun [getConcentration](../-camera-see/index.md#-1328510210%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[T](index.md)> |
| [getContext](../-abstract-move-node/get-context.md) | [jvm]<br>override fun [getContext](../-abstract-move-node/get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getCurrentPosition](../-levy-walk/index.md#1706811851%2FFunctions%2F-267951372) | [jvm]<br>fun [getCurrentPosition](../-levy-walk/index.md#1706811851%2FFunctions%2F-267951372)(): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md) |
| [getEnvironment](../-levy-walk/index.md#-391547238%2FFunctions%2F-267951372) | [jvm]<br>open fun [getEnvironment](../-levy-walk/index.md#-391547238%2FFunctions%2F-267951372)(): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)> |
| [getNextPosition](../-abstract-steering-action/get-next-position.md) | [jvm]<br>open override fun [getNextPosition](../-abstract-steering-action/get-next-position.md)(): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md) |
| [getNodePosition](../-levy-walk/index.md#1299827309%2FFunctions%2F-267951372) | [jvm]<br>fun [getNodePosition](../-levy-walk/index.md#1299827309%2FFunctions%2F-267951372)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md) | [jvm]<br>override fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [isAbsolute](../-levy-walk/index.md#9650230%2FFunctions%2F-267951372) | [jvm]<br>fun [isAbsolute](../-levy-walk/index.md#9650230%2FFunctions%2F-267951372)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [moveToFinal](../-cognitive-agent-reach-known-destination/index.md#1867563439%2FFunctions%2F-267951372) | [jvm]<br>open override fun [moveToFinal](../-cognitive-agent-reach-known-destination/index.md#1867563439%2FFunctions%2F-267951372)(destination: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md))<br>Moves the pedestrian to the given final [destination](../-cognitive-agent-reach-known-destination/index.md#1867563439%2FFunctions%2F-267951372), which must be inside [currentRoom](../-abstract-navigation-action/current-room.md). |
| [nextPosition](../-cognitive-agent-navigation-action2-d/next-position.md) | [jvm]<br>open override fun [nextPosition](../-cognitive-agent-navigation-action2-d/next-position.md)(): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)<br>The position the owner of this action moves to when it is executed, in relative coordinates with respect to its current position. |
| [nodeContains](../-camera-see/index.md#1662898740%2FFunctions%2F-267951372) | [jvm]<br>fun [nodeContains](../-camera-see/index.md#1662898740%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [removeConcentration](../-camera-see/index.md#-151459758%2FFunctions%2F-267951372) | [jvm]<br>fun [removeConcentration](../-camera-see/index.md#-151459758%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)) |
| [setConcentration](../-toggle-molecule-randomly/index.md#-330064727%2FFunctions%2F-267951372) | [jvm]<br>fun [setConcentration](../-toggle-molecule-randomly/index.md#-330064727%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), p1: [T](index.md)) |
| [stop](../../it.unibo.alchemist.model.interfaces/-navigation-action/stop.md) | [jvm]<br>open fun [stop](../../it.unibo.alchemist.model.interfaces/-navigation-action/stop.md)()<br>Stops moving the pedestrian. |
| [toString](../-abstract-action/to-string.md) | [jvm]<br>open override fun [toString](../-abstract-action/to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [update](../-abstract-navigation-action/update.md) | [jvm]<br>open fun [update](../-abstract-navigation-action/update.md)()<br>Updates the internal state but does not move the pedestrian. |

## Properties

| Name | Summary |
|---|---|
| [currentRoom](index.md#-843555804%2FProperties%2F-267951372) | [jvm]<br>open override var [currentRoom](index.md#-843555804%2FProperties%2F-267951372): [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md)?<br>The room (= environment's area) the [pedestrian](../-abstract-navigation-action/pedestrian.md) is into, this is cached and updated every time [update](../-abstract-navigation-action/update.md) is called so as to avoid potentially costly re-computations. |
| [desiredPosition](index.md#1813372309%2FProperties%2F-267951372) | [jvm]<br>val [desiredPosition](index.md#1813372309%2FProperties%2F-267951372): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)<br>The position the pedestrian wants to reach. |
| [environment](index.md#811993317%2FProperties%2F-267951372) | [jvm]<br>open override val [environment](index.md#811993317%2FProperties%2F-267951372): [Euclidean2DEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment-with-graph/index.md)<*, [T](index.md), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.md)><br>The environment the [pedestrian](../-cognitive-agent-navigation-action2-d/index.md#698091694%2FProperties%2F-267951372) is into. |
| [maxWalk](index.md#-2090156949%2FProperties%2F-267951372) | [jvm]<br>open val [maxWalk](index.md#-2090156949%2FProperties%2F-267951372): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The maximum distance the pedestrian can walk, this is a length. |
| [pedestrian](index.md#758548903%2FProperties%2F-267951372) | [jvm]<br>override val [pedestrian](index.md#758548903%2FProperties%2F-267951372): [OrientingPedestrian](../../it.unibo.alchemist.model.interfaces/-orienting-pedestrian/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.md), [L](index.md), [R](index.md)><br>The owner of this action. |
| [pedestrianPosition](index.md#-599697794%2FProperties%2F-267951372) | [jvm]<br>open lateinit override var [pedestrianPosition](index.md#-599697794%2FProperties%2F-267951372): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)<br>The position of the [pedestrian](../-abstract-navigation-action/pedestrian.md) in the [environment](../-abstract-navigation-action/environment.md), this is cached and updated every time [update](../-abstract-navigation-action/update.md) is called so as to avoid potentially costly re-computations. |

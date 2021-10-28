//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[AbstractNavigationAction](index.md)

# AbstractNavigationAction

[jvm]\
abstract class [AbstractNavigationAction](index.md)<[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[P](index.md)>, [L](index.md) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.md)<[P](index.md), [A](index.md)>, [R](index.md), [N](index.md) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.md)<[P](index.md), [A](index.md)>, [E](index.md)>(**environment**: [EnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-environment-with-graph/index.md)<*, [T](index.md), [P](index.md), [A](index.md), [N](index.md), [E](index.md)>, **reaction**: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>, **pedestrian**: [OrientingPedestrian](../../it.unibo.alchemist.model.interfaces/-orienting-pedestrian/index.md)<[T](index.md), [P](index.md), [A](index.md), [L](index.md), [R](index.md)>) : [AbstractSteeringAction](../-abstract-steering-action/index.md)<[T](index.md), [P](index.md), [A](index.md)> , [NavigationAction](../../it.unibo.alchemist.model.interfaces/-navigation-action/index.md)<[T](index.md), [P](index.md), [A](index.md), [L](index.md), [R](index.md), [N](index.md), [E](index.md)> 

An abstract [NavigationAction](../../it.unibo.alchemist.model.interfaces/-navigation-action/index.md), taking care of properly moving the pedestrian in the environment while delegating the decision on where to move it to a [NavigationStrategy](../../it.unibo.alchemist.model.interfaces/-navigation-strategy/index.md).

## Parameters

jvm

| | |
|---|---|
| T | the concentration type. |
| P | the [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md) type and [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md) type for the space the pedestrian is into. |
| A | the transformations supported by the shapes in this space. |
| L | the type of landmarks of the pedestrian's cognitive map. |
| R | the type of edges of the pedestrian's cognitive map, representing the [R](index.md)elations between landmarks. |
| N | the type of nodes of the navigation graph provided by the [environment](environment.md). |
| E | the type of edges of the navigation graph provided by the [environment](environment.md). |

## Constructors

| | |
|---|---|
| [AbstractNavigationAction](-abstract-navigation-action.md) | [jvm]<br>fun <[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[P](index.md)>, [L](index.md) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.md)<[P](index.md), [A](index.md)>, [R](index.md), [N](index.md) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.md)<[P](index.md), [A](index.md)>, [E](index.md)> [AbstractNavigationAction](-abstract-navigation-action.md)(environment: [EnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-environment-with-graph/index.md)<*, [T](index.md), [P](index.md), [A](index.md), [N](index.md), [E](index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>, pedestrian: [OrientingPedestrian](../../it.unibo.alchemist.model.interfaces/-orienting-pedestrian/index.md)<[T](index.md), [P](index.md), [A](index.md), [L](index.md), [R](index.md)>)<br>the concentration type. |

## Functions

| Name | Summary |
|---|---|
| [cloneAction](../-abstract-steering-action/clone-action.md) | [jvm]<br>open override fun [cloneAction](../-abstract-steering-action/clone-action.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.md)<[T](index.md)> |
| [crossDoor](../../it.unibo.alchemist.model.interfaces/-navigation-action/cross-door.md) | [jvm]<br>abstract fun [crossDoor](../../it.unibo.alchemist.model.interfaces/-navigation-action/cross-door.md)(door: [E](index.md))<br>Moves the pedestrian across the provided [door](../../it.unibo.alchemist.model.interfaces/-navigation-action/cross-door.md), which must be among [doorsInSight](../../it.unibo.alchemist.model.interfaces/-navigation-action/doors-in-sight.md). |
| [declareDependencyTo](../-camera-see/index.md#1970369254%2FFunctions%2F-267951372) | [jvm]<br>fun [declareDependencyTo](../-camera-see/index.md#1970369254%2FFunctions%2F-267951372)(p0: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)) |
| [doorsInSight](doors-in-sight.md) | [jvm]<br>open override fun [doorsInSight](doors-in-sight.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[E](index.md)> |
| [execute](../-abstract-move-node/execute.md) | [jvm]<br>open override fun [execute](../-abstract-move-node/execute.md)() |
| [getConcentration](../-camera-see/index.md#-1328510210%2FFunctions%2F-267951372) | [jvm]<br>fun [getConcentration](../-camera-see/index.md#-1328510210%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[T](index.md)> |
| [getContext](../-abstract-move-node/get-context.md) | [jvm]<br>override fun [getContext](../-abstract-move-node/get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getCurrentPosition](../-levy-walk/index.md#1706811851%2FFunctions%2F-267951372) | [jvm]<br>fun [getCurrentPosition](../-levy-walk/index.md#1706811851%2FFunctions%2F-267951372)(): [P](index.md) |
| [getEnvironment](../-levy-walk/index.md#-391547238%2FFunctions%2F-267951372) | [jvm]<br>open fun [getEnvironment](../-levy-walk/index.md#-391547238%2FFunctions%2F-267951372)(): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [P](index.md)> |
| [getNextPosition](../-abstract-steering-action/get-next-position.md) | [jvm]<br>open override fun [getNextPosition](../-abstract-steering-action/get-next-position.md)(): [P](index.md) |
| [getNodePosition](../-levy-walk/index.md#1299827309%2FFunctions%2F-267951372) | [jvm]<br>fun [getNodePosition](../-levy-walk/index.md#1299827309%2FFunctions%2F-267951372)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>): [P](index.md) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md) | [jvm]<br>override fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [isAbsolute](../-levy-walk/index.md#9650230%2FFunctions%2F-267951372) | [jvm]<br>fun [isAbsolute](../-levy-walk/index.md#9650230%2FFunctions%2F-267951372)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [moveToFinal](move-to-final.md) | [jvm]<br>open override fun [moveToFinal](move-to-final.md)(destination: [P](index.md))<br>Moves the pedestrian to the given final [destination](move-to-final.md), which must be inside [currentRoom](current-room.md). |
| [nextPosition](../../it.unibo.alchemist.model.interfaces/-steering-action/next-position.md) | [jvm]<br>abstract fun [nextPosition](../../it.unibo.alchemist.model.interfaces/-steering-action/next-position.md)(): [P](index.md)<br>The position the owner of this action moves to when it is executed, in relative coordinates with respect to its current position. |
| [nodeContains](../-camera-see/index.md#1662898740%2FFunctions%2F-267951372) | [jvm]<br>fun [nodeContains](../-camera-see/index.md#1662898740%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [removeConcentration](../-camera-see/index.md#-151459758%2FFunctions%2F-267951372) | [jvm]<br>fun [removeConcentration](../-camera-see/index.md#-151459758%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)) |
| [setConcentration](../-toggle-molecule-randomly/index.md#-330064727%2FFunctions%2F-267951372) | [jvm]<br>fun [setConcentration](../-toggle-molecule-randomly/index.md#-330064727%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), p1: [T](index.md)) |
| [stop](../../it.unibo.alchemist.model.interfaces/-navigation-action/stop.md) | [jvm]<br>open fun [stop](../../it.unibo.alchemist.model.interfaces/-navigation-action/stop.md)()<br>Stops moving the pedestrian. |
| [toString](../-abstract-action/to-string.md) | [jvm]<br>open override fun [toString](../-abstract-action/to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [update](update.md) | [jvm]<br>open fun [update](update.md)()<br>Updates the internal state but does not move the pedestrian. |

## Properties

| Name | Summary |
|---|---|
| [currentRoom](current-room.md) | [jvm]<br>open override var [currentRoom](current-room.md): [N](index.md)? = null<br>The room (= environment's area) the [pedestrian](pedestrian.md) is into, this is cached and updated every time [update](update.md) is called so as to avoid potentially costly re-computations. |
| [desiredPosition](desired-position.md) | [jvm]<br>val [desiredPosition](desired-position.md): [P](index.md)<br>The position the pedestrian wants to reach. |
| [environment](environment.md) | [jvm]<br>open override val [environment](environment.md): [EnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-environment-with-graph/index.md)<*, [T](index.md), [P](index.md), [A](index.md), [N](index.md), [E](index.md)><br>The environment the [pedestrian](pedestrian.md) is into. |
| [maxWalk](index.md#1369076767%2FProperties%2F-267951372) | [jvm]<br>open val [maxWalk](index.md#1369076767%2FProperties%2F-267951372): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The maximum distance the pedestrian can walk, this is a length. |
| [pedestrian](pedestrian.md) | [jvm]<br>override val [pedestrian](pedestrian.md): [OrientingPedestrian](../../it.unibo.alchemist.model.interfaces/-orienting-pedestrian/index.md)<[T](index.md), [P](index.md), [A](index.md), [L](index.md), [R](index.md)><br>The owner of this action. |
| [pedestrianPosition](pedestrian-position.md) | [jvm]<br>open lateinit override var [pedestrianPosition](pedestrian-position.md): [P](index.md)<br>The position of the [pedestrian](pedestrian.md) in the [environment](environment.md), this is cached and updated every time [update](update.md) is called so as to avoid potentially costly re-computations. |

## Inheritors

| Name |
|---|
| [CognitiveAgentNavigationAction2D](../-cognitive-agent-navigation-action2-d/index.md) |

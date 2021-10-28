---
title: AbstractNavigationAction
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[AbstractNavigationAction](index.html)



# AbstractNavigationAction



[jvm]\
abstract class [AbstractNavigationAction](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[P](index.html)>, [L](index.html) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[P](index.html), [A](index.html)>, [R](index.html), [N](index.html) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[P](index.html), [A](index.html)>, [E](index.html)>(**environment**: [EnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-environment-with-graph/index.html)<*, [T](index.html), [P](index.html), [A](index.html), [N](index.html), [E](index.html)>, **reaction**: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>, **pedestrian**: [OrientingPedestrian](../../it.unibo.alchemist.model.interfaces/-orienting-pedestrian/index.html)<[T](index.html), [P](index.html), [A](index.html), [L](index.html), [R](index.html)>) : [AbstractSteeringAction](../-abstract-steering-action/index.html)<[T](index.html), [P](index.html), [A](index.html)> , [NavigationAction](../../it.unibo.alchemist.model.interfaces/-navigation-action/index.html)<[T](index.html), [P](index.html), [A](index.html), [L](index.html), [R](index.html), [N](index.html), [E](index.html)> 

An abstract [NavigationAction](../../it.unibo.alchemist.model.interfaces/-navigation-action/index.html), taking care of properly moving the pedestrian in the environment while delegating the decision on where to move it to a [NavigationStrategy](../../it.unibo.alchemist.model.interfaces/-navigation-strategy/index.html).



## Parameters


jvm

| | |
|---|---|
| T | the concentration type. |
| P | the [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html) type and [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html) type for the space the pedestrian is into. |
| A | the transformations supported by the shapes in this space. |
| L | the type of landmarks of the pedestrian's cognitive map. |
| R | the type of edges of the pedestrian's cognitive map, representing the [R](index.html)elations between landmarks. |
| N | the type of nodes of the navigation graph provided by the [environment](environment.html). |
| E | the type of edges of the navigation graph provided by the [environment](environment.html). |



## Constructors


| | |
|---|---|
| [AbstractNavigationAction](-abstract-navigation-action.html) | [jvm]<br>fun <[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[P](index.html)>, [L](index.html) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[P](index.html), [A](index.html)>, [R](index.html), [N](index.html) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[P](index.html), [A](index.html)>, [E](index.html)> [AbstractNavigationAction](-abstract-navigation-action.html)(environment: [EnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-environment-with-graph/index.html)<*, [T](index.html), [P](index.html), [A](index.html), [N](index.html), [E](index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>, pedestrian: [OrientingPedestrian](../../it.unibo.alchemist.model.interfaces/-orienting-pedestrian/index.html)<[T](index.html), [P](index.html), [A](index.html), [L](index.html), [R](index.html)>)<br>the concentration type. |


## Functions


| Name | Summary |
|---|---|
| [cloneAction](../-abstract-steering-action/clone-action.html) | [jvm]<br>open override fun [cloneAction](../-abstract-steering-action/clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](index.html)> |
| [crossDoor](../../it.unibo.alchemist.model.interfaces/-navigation-action/cross-door.html) | [jvm]<br>abstract fun [crossDoor](../../it.unibo.alchemist.model.interfaces/-navigation-action/cross-door.html)(door: [E](index.html))<br>Moves the pedestrian across the provided [door](../../it.unibo.alchemist.model.interfaces/-navigation-action/cross-door.html), which must be among [doorsInSight](../../it.unibo.alchemist.model.interfaces/-navigation-action/doors-in-sight.html). |
| [declareDependencyTo](../-camera-see/index.html#1970369254%2FFunctions%2F-134779887) | [jvm]<br>fun [declareDependencyTo](../-camera-see/index.html#1970369254%2FFunctions%2F-134779887)(p0: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)) |
| [doorsInSight](doors-in-sight.html) | [jvm]<br>open override fun [doorsInSight](doors-in-sight.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[E](index.html)> |
| [execute](../-abstract-move-node/execute.html) | [jvm]<br>open override fun [execute](../-abstract-move-node/execute.html)() |
| [getConcentration](../-camera-see/index.html#-1328510210%2FFunctions%2F-134779887) | [jvm]<br>fun [getConcentration](../-camera-see/index.html#-1328510210%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[T](index.html)> |
| [getContext](../-abstract-move-node/get-context.html) | [jvm]<br>override fun [getContext](../-abstract-move-node/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getCurrentPosition](../-levy-walk/index.html#1706811851%2FFunctions%2F-134779887) | [jvm]<br>fun [getCurrentPosition](../-levy-walk/index.html#1706811851%2FFunctions%2F-134779887)(): [P](index.html) |
| [getEnvironment](../-levy-walk/index.html#-391547238%2FFunctions%2F-134779887) | [jvm]<br>open fun [getEnvironment](../-levy-walk/index.html#-391547238%2FFunctions%2F-134779887)(): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](index.html)> |
| [getNextPosition](../-abstract-steering-action/get-next-position.html) | [jvm]<br>open override fun [getNextPosition](../-abstract-steering-action/get-next-position.html)(): [P](index.html) |
| [getNodePosition](../-levy-walk/index.html#1299827309%2FFunctions%2F-134779887) | [jvm]<br>fun [getNodePosition](../-levy-walk/index.html#1299827309%2FFunctions%2F-134779887)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>): [P](index.html) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html) | [jvm]<br>override fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [isAbsolute](../-levy-walk/index.html#9650230%2FFunctions%2F-134779887) | [jvm]<br>fun [isAbsolute](../-levy-walk/index.html#9650230%2FFunctions%2F-134779887)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [moveToFinal](move-to-final.html) | [jvm]<br>open override fun [moveToFinal](move-to-final.html)(destination: [P](index.html))<br>Moves the pedestrian to the given final [destination](move-to-final.html), which must be inside [currentRoom](current-room.html). |
| [nextPosition](../../it.unibo.alchemist.model.interfaces/-steering-action/next-position.html) | [jvm]<br>abstract fun [nextPosition](../../it.unibo.alchemist.model.interfaces/-steering-action/next-position.html)(): [P](index.html)<br>The position the owner of this action moves to when it is executed, in relative coordinates with respect to its current position. |
| [nodeContains](../-camera-see/index.html#1662898740%2FFunctions%2F-134779887) | [jvm]<br>fun [nodeContains](../-camera-see/index.html#1662898740%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [removeConcentration](../-camera-see/index.html#-151459758%2FFunctions%2F-134779887) | [jvm]<br>fun [removeConcentration](../-camera-see/index.html#-151459758%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)) |
| [setConcentration](../-toggle-molecule-randomly/index.html#-330064727%2FFunctions%2F-134779887) | [jvm]<br>fun [setConcentration](../-toggle-molecule-randomly/index.html#-330064727%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), p1: [T](index.html)) |
| [stop](../../it.unibo.alchemist.model.interfaces/-navigation-action/stop.html) | [jvm]<br>open fun [stop](../../it.unibo.alchemist.model.interfaces/-navigation-action/stop.html)()<br>Stops moving the pedestrian. |
| [toString](../-abstract-action/to-string.html) | [jvm]<br>open override fun [toString](../-abstract-action/to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [update](update.html) | [jvm]<br>open fun [update](update.html)()<br>Updates the internal state but does not move the pedestrian. |


## Properties


| Name | Summary |
|---|---|
| [currentRoom](current-room.html) | [jvm]<br>open override var [currentRoom](current-room.html): [N](index.html)? = null<br>The room (= environment's area) the [pedestrian](pedestrian.html) is into, this is cached and updated every time [update](update.html) is called so as to avoid potentially costly re-computations. |
| [desiredPosition](desired-position.html) | [jvm]<br>val [desiredPosition](desired-position.html): [P](index.html)<br>The position the pedestrian wants to reach. |
| [environment](environment.html) | [jvm]<br>open override val [environment](environment.html): [EnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-environment-with-graph/index.html)<*, [T](index.html), [P](index.html), [A](index.html), [N](index.html), [E](index.html)><br>The environment the [pedestrian](pedestrian.html) is into. |
| [maxWalk](index.html#1369076767%2FProperties%2F-134779887) | [jvm]<br>open val [maxWalk](index.html#1369076767%2FProperties%2F-134779887): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The maximum distance the pedestrian can walk, this is a length. |
| [pedestrian](pedestrian.html) | [jvm]<br>override val [pedestrian](pedestrian.html): [OrientingPedestrian](../../it.unibo.alchemist.model.interfaces/-orienting-pedestrian/index.html)<[T](index.html), [P](index.html), [A](index.html), [L](index.html), [R](index.html)><br>The owner of this action. |
| [pedestrianPosition](pedestrian-position.html) | [jvm]<br>open lateinit override var [pedestrianPosition](pedestrian-position.html): [P](index.html)<br>The position of the [pedestrian](pedestrian.html) in the [environment](environment.html), this is cached and updated every time [update](update.html) is called so as to avoid potentially costly re-computations. |


## Inheritors


| Name |
|---|
| [CognitiveAgentNavigationAction2D](../-cognitive-agent-navigation-action2-d/index.html) |


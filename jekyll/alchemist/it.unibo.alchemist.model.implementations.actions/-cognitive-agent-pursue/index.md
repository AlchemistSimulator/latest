---
title: CognitiveAgentPursue
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[CognitiveAgentPursue](index.html)



# CognitiveAgentPursue



[jvm]\
class [CognitiveAgentPursue](index.html)<[T](index.html), [L](index.html) : [Euclidean2DConvexShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.html#-786369621%2FClasslikes%2F-134779887), [R](index.html)>(**environment**: [Euclidean2DEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment-with-graph/index.html)<*, [T](index.html), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.html)>, **reaction**: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>, **pedestrian**: [OrientingPedestrian2D](../../it.unibo.alchemist.model.interfaces/index.html#1465026919%2FClasslikes%2F-134779887)<[T](index.html), [L](index.html), [R](index.html)>, **destination**: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)) : [CognitiveAgentNavigationAction2D](../-cognitive-agent-navigation-action2-d/index.html)<[T](index.html), [L](index.html), [R](index.html)> 

A [NavigationAction](../../it.unibo.alchemist.model.interfaces/-navigation-action/index.html) using [Pursuing](../../it.unibo.alchemist.model.implementations.actions.navigationstrategies/-pursuing/index.html) navigation strategy.



## Parameters


jvm

| | |
|---|---|
| T | the concentration type. |
| L | the type of landmarks of the pedestrian's cognitive map. |
| R | the type of edges of the pedestrian's cognitive map, representing the [R](index.html)elations between landmarks. |



## Constructors


| | |
|---|---|
| [CognitiveAgentPursue](-cognitive-agent-pursue.html) | [jvm]<br>fun <[T](index.html)> [CognitiveAgentPursue](-cognitive-agent-pursue.html)(environment: [Euclidean2DEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment-with-graph/index.html)<*, [T](index.html), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>, pedestrian: [OrientingPedestrian2D](../../it.unibo.alchemist.model.interfaces/index.html#1465026919%2FClasslikes%2F-134779887)<[T](index.html), [L](index.html), [R](index.html)>, vararg destination: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html))<br>the concentration type. |


## Functions


| Name | Summary |
|---|---|
| [cloneAction](../-abstract-steering-action/clone-action.html) | [jvm]<br>open override fun [cloneAction](../-abstract-steering-action/clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](index.html)> |
| [crossDoor](../-cognitive-agent-navigation-action2-d/cross-door.html) | [jvm]<br>open override fun [crossDoor](../-cognitive-agent-navigation-action2-d/cross-door.html)(door: [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.html))<br>Moves the pedestrian across the provided [door](../-cognitive-agent-navigation-action2-d/cross-door.html), which must be among doorsInSight. |
| [declareDependencyTo](../-camera-see/index.html#1970369254%2FFunctions%2F-134779887) | [jvm]<br>fun [declareDependencyTo](../-camera-see/index.html#1970369254%2FFunctions%2F-134779887)(p0: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)) |
| [doorsInSight](../-abstract-navigation-action/doors-in-sight.html) | [jvm]<br>open override fun [doorsInSight](../-abstract-navigation-action/doors-in-sight.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.html)> |
| [execute](../-abstract-move-node/execute.html) | [jvm]<br>open override fun [execute](../-abstract-move-node/execute.html)() |
| [getConcentration](../-camera-see/index.html#-1328510210%2FFunctions%2F-134779887) | [jvm]<br>fun [getConcentration](../-camera-see/index.html#-1328510210%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[T](index.html)> |
| [getContext](../-abstract-move-node/get-context.html) | [jvm]<br>override fun [getContext](../-abstract-move-node/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getCurrentPosition](../-levy-walk/index.html#1706811851%2FFunctions%2F-134779887) | [jvm]<br>fun [getCurrentPosition](../-levy-walk/index.html#1706811851%2FFunctions%2F-134779887)(): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html) |
| [getEnvironment](../-levy-walk/index.html#-391547238%2FFunctions%2F-134779887) | [jvm]<br>open fun [getEnvironment](../-levy-walk/index.html#-391547238%2FFunctions%2F-134779887)(): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)> |
| [getNextPosition](../-abstract-steering-action/get-next-position.html) | [jvm]<br>open override fun [getNextPosition](../-abstract-steering-action/get-next-position.html)(): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html) |
| [getNodePosition](../-levy-walk/index.html#1299827309%2FFunctions%2F-134779887) | [jvm]<br>fun [getNodePosition](../-levy-walk/index.html#1299827309%2FFunctions%2F-134779887)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html) | [jvm]<br>override fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [isAbsolute](../-levy-walk/index.html#9650230%2FFunctions%2F-134779887) | [jvm]<br>fun [isAbsolute](../-levy-walk/index.html#9650230%2FFunctions%2F-134779887)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [moveToFinal](../-cognitive-agent-reach-known-destination/index.html#1867563439%2FFunctions%2F-134779887) | [jvm]<br>open override fun [moveToFinal](../-cognitive-agent-reach-known-destination/index.html#1867563439%2FFunctions%2F-134779887)(destination: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html))<br>Moves the pedestrian to the given final [destination](../-cognitive-agent-reach-known-destination/index.html#1867563439%2FFunctions%2F-134779887), which must be inside [currentRoom](../-abstract-navigation-action/current-room.html). |
| [nextPosition](../-cognitive-agent-navigation-action2-d/next-position.html) | [jvm]<br>open override fun [nextPosition](../-cognitive-agent-navigation-action2-d/next-position.html)(): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)<br>The position the owner of this action moves to when it is executed, in relative coordinates with respect to its current position. |
| [nodeContains](../-camera-see/index.html#1662898740%2FFunctions%2F-134779887) | [jvm]<br>fun [nodeContains](../-camera-see/index.html#1662898740%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [removeConcentration](../-camera-see/index.html#-151459758%2FFunctions%2F-134779887) | [jvm]<br>fun [removeConcentration](../-camera-see/index.html#-151459758%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)) |
| [setConcentration](../-toggle-molecule-randomly/index.html#-330064727%2FFunctions%2F-134779887) | [jvm]<br>fun [setConcentration](../-toggle-molecule-randomly/index.html#-330064727%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), p1: [T](index.html)) |
| [stop](../../it.unibo.alchemist.model.interfaces/-navigation-action/stop.html) | [jvm]<br>open fun [stop](../../it.unibo.alchemist.model.interfaces/-navigation-action/stop.html)()<br>Stops moving the pedestrian. |
| [toString](../-abstract-action/to-string.html) | [jvm]<br>open override fun [toString](../-abstract-action/to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [update](../-abstract-navigation-action/update.html) | [jvm]<br>open fun [update](../-abstract-navigation-action/update.html)()<br>Updates the internal state but does not move the pedestrian. |


## Properties


| Name | Summary |
|---|---|
| [currentRoom](index.html#-641364765%2FProperties%2F-134779887) | [jvm]<br>open override var [currentRoom](index.html#-641364765%2FProperties%2F-134779887): [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html)?<br>The room (= environment's area) the [pedestrian](../-abstract-navigation-action/pedestrian.html) is into, this is cached and updated every time [update](../-abstract-navigation-action/update.html) is called so as to avoid potentially costly re-computations. |
| [desiredPosition](index.html#1485739732%2FProperties%2F-134779887) | [jvm]<br>val [desiredPosition](index.html#1485739732%2FProperties%2F-134779887): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)<br>The position the pedestrian wants to reach. |
| [environment](index.html#1014184356%2FProperties%2F-134779887) | [jvm]<br>open override val [environment](index.html#1014184356%2FProperties%2F-134779887): [Euclidean2DEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment-with-graph/index.html)<*, [T](index.html), [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), [Euclidean2DPassage](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-euclidean2-d-passage/index.html)><br>The environment the [pedestrian](../-cognitive-agent-navigation-action2-d/index.html#698091694%2FProperties%2F-134779887) is into. |
| [maxWalk](index.html#-1091296086%2FProperties%2F-134779887) | [jvm]<br>open val [maxWalk](index.html#-1091296086%2FProperties%2F-134779887): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The maximum distance the pedestrian can walk, this is a length. |
| [pedestrian](index.html#-2005875448%2FProperties%2F-134779887) | [jvm]<br>override val [pedestrian](index.html#-2005875448%2FProperties%2F-134779887): [OrientingPedestrian](../../it.unibo.alchemist.model.interfaces/-orienting-pedestrian/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html), [L](index.html), [R](index.html)><br>The owner of this action. |
| [pedestrianPosition](index.html#1358864607%2FProperties%2F-134779887) | [jvm]<br>open lateinit override var [pedestrianPosition](index.html#1358864607%2FProperties%2F-134779887): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)<br>The position of the [pedestrian](../-abstract-navigation-action/pedestrian.html) in the [environment](../-abstract-navigation-action/environment.html), this is cached and updated every time [update](../-abstract-navigation-action/update.html) is called so as to avoid potentially costly re-computations. |

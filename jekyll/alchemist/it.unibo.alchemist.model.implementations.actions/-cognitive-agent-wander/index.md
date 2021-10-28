---
title: CognitiveAgentWander
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[CognitiveAgentWander](index.html)



# CognitiveAgentWander



[jvm]\
open class [CognitiveAgentWander](index.html)<[T](index.html)>(**environment**: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.html)<[T](index.html)>, **reaction**: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>, **pedestrian**: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.html)<[T](index.html)>, **randomGenerator**: RandomGenerator, **offset**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **radius**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [AbstractSteeringActionWithTarget](../-abstract-steering-action-with-target/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html)> 

Give the impression of a random walk through the environment targeting an ever changing pseudo-randomly point of a circumference at a given distance and with a given radius from the current pedestrian position.



## Parameters


jvm

| | |
|---|---|
| environment | the environment inside which the pedestrian moves. |
| pedestrian | the owner of this action. |
| randomGenerator | the simulation {@link RandomGenerator}. |
| offset | the distance from the pedestrian position of the center of the circle. |
| radius | the radius of the circle. |



## Constructors


| | |
|---|---|
| [CognitiveAgentWander](-cognitive-agent-wander.html) | [jvm]<br>fun <[T](index.html)> [CognitiveAgentWander](-cognitive-agent-wander.html)(environment: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.html)<[T](index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>, pedestrian: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.html)<[T](index.html)>, randomGenerator: RandomGenerator, offset: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>    the environment inside which the pedestrian moves. |


## Functions


| Name | Summary |
|---|---|
| [cloneAction](../-abstract-steering-action/clone-action.html) | [jvm]<br>open override fun [cloneAction](../-abstract-steering-action/clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](index.html)> |
| [declareDependencyTo](../-camera-see/index.html#1970369254%2FFunctions%2F-134779887) | [jvm]<br>fun [declareDependencyTo](../-camera-see/index.html#1970369254%2FFunctions%2F-134779887)(p0: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)) |
| [execute](../-abstract-move-node/execute.html) | [jvm]<br>open override fun [execute](../-abstract-move-node/execute.html)() |
| [getConcentration](../-camera-see/index.html#-1328510210%2FFunctions%2F-134779887) | [jvm]<br>fun [getConcentration](../-camera-see/index.html#-1328510210%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[T](index.html)> |
| [getContext](../-abstract-move-node/get-context.html) | [jvm]<br>override fun [getContext](../-abstract-move-node/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getCurrentPosition](../-levy-walk/index.html#1706811851%2FFunctions%2F-134779887) | [jvm]<br>fun [getCurrentPosition](../-levy-walk/index.html#1706811851%2FFunctions%2F-134779887)(): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html) |
| [getEnvironment](../-levy-walk/index.html#-391547238%2FFunctions%2F-134779887) | [jvm]<br>open fun [getEnvironment](../-levy-walk/index.html#-391547238%2FFunctions%2F-134779887)(): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)> |
| [getNextPosition](../-abstract-steering-action/get-next-position.html) | [jvm]<br>open override fun [getNextPosition](../-abstract-steering-action/get-next-position.html)(): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html) |
| [getNodePosition](../-levy-walk/index.html#1299827309%2FFunctions%2F-134779887) | [jvm]<br>fun [getNodePosition](../-levy-walk/index.html#1299827309%2FFunctions%2F-134779887)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html) | [jvm]<br>override fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [isAbsolute](../-levy-walk/index.html#9650230%2FFunctions%2F-134779887) | [jvm]<br>fun [isAbsolute](../-levy-walk/index.html#9650230%2FFunctions%2F-134779887)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [nextPosition](next-position.html) | [jvm]<br>open override fun [nextPosition](next-position.html)(): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html) |
| [nodeContains](../-camera-see/index.html#1662898740%2FFunctions%2F-134779887) | [jvm]<br>fun [nodeContains](../-camera-see/index.html#1662898740%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [removeConcentration](../-camera-see/index.html#-151459758%2FFunctions%2F-134779887) | [jvm]<br>fun [removeConcentration](../-camera-see/index.html#-151459758%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)) |
| [setConcentration](../-toggle-molecule-randomly/index.html#-330064727%2FFunctions%2F-134779887) | [jvm]<br>fun [setConcentration](../-toggle-molecule-randomly/index.html#-330064727%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), p1: [T](index.html)) |
| [target](../-abstract-steering-action-with-target/target.html) | [jvm]<br>open override fun [target](../-abstract-steering-action-with-target/target.html)(): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)<br>The position the owner of this action moves towards, in absolute coordinates. |
| [toString](../-abstract-action/to-string.html) | [jvm]<br>open override fun [toString](../-abstract-action/to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |


## Properties


| Name | Summary |
|---|---|
| [maxWalk](index.html#843319539%2FProperties%2F-134779887) | [jvm]<br>open val [maxWalk](index.html#843319539%2FProperties%2F-134779887): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The maximum distance the pedestrian can walk, this is a length. |


//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[CognitiveAgentWander](index.md)

# CognitiveAgentWander

[jvm]\
open class [CognitiveAgentWander](index.md)<[T](index.md)>(**environment**: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md)<[T](index.md)>, **reaction**: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>, **pedestrian**: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.md)<[T](index.md)>, **randomGenerator**: RandomGenerator, **offset**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **radius**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [AbstractSteeringActionWithTarget](../-abstract-steering-action-with-target/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.md)> 

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
| [CognitiveAgentWander](-cognitive-agent-wander.md) | [jvm]<br>fun <[T](index.md)> [CognitiveAgentWander](-cognitive-agent-wander.md)(environment: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md)<[T](index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>, pedestrian: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.md)<[T](index.md)>, randomGenerator: RandomGenerator, offset: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>    the environment inside which the pedestrian moves. |

## Functions

| Name | Summary |
|---|---|
| [cloneAction](../-abstract-steering-action/clone-action.md) | [jvm]<br>open override fun [cloneAction](../-abstract-steering-action/clone-action.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.md)<[T](index.md)> |
| [declareDependencyTo](../-camera-see/index.md#1970369254%2FFunctions%2F-267951372) | [jvm]<br>fun [declareDependencyTo](../-camera-see/index.md#1970369254%2FFunctions%2F-267951372)(p0: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)) |
| [execute](../-abstract-move-node/execute.md) | [jvm]<br>open override fun [execute](../-abstract-move-node/execute.md)() |
| [getConcentration](../-camera-see/index.md#-1328510210%2FFunctions%2F-267951372) | [jvm]<br>fun [getConcentration](../-camera-see/index.md#-1328510210%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[T](index.md)> |
| [getContext](../-abstract-move-node/get-context.md) | [jvm]<br>override fun [getContext](../-abstract-move-node/get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getCurrentPosition](../-levy-walk/index.md#1706811851%2FFunctions%2F-267951372) | [jvm]<br>fun [getCurrentPosition](../-levy-walk/index.md#1706811851%2FFunctions%2F-267951372)(): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md) |
| [getEnvironment](../-levy-walk/index.md#-391547238%2FFunctions%2F-267951372) | [jvm]<br>open fun [getEnvironment](../-levy-walk/index.md#-391547238%2FFunctions%2F-267951372)(): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)> |
| [getNextPosition](../-abstract-steering-action/get-next-position.md) | [jvm]<br>open override fun [getNextPosition](../-abstract-steering-action/get-next-position.md)(): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md) |
| [getNodePosition](../-levy-walk/index.md#1299827309%2FFunctions%2F-267951372) | [jvm]<br>fun [getNodePosition](../-levy-walk/index.md#1299827309%2FFunctions%2F-267951372)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md) | [jvm]<br>override fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [isAbsolute](../-levy-walk/index.md#9650230%2FFunctions%2F-267951372) | [jvm]<br>fun [isAbsolute](../-levy-walk/index.md#9650230%2FFunctions%2F-267951372)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [nextPosition](next-position.md) | [jvm]<br>open override fun [nextPosition](next-position.md)(): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md) |
| [nodeContains](../-camera-see/index.md#1662898740%2FFunctions%2F-267951372) | [jvm]<br>fun [nodeContains](../-camera-see/index.md#1662898740%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [removeConcentration](../-camera-see/index.md#-151459758%2FFunctions%2F-267951372) | [jvm]<br>fun [removeConcentration](../-camera-see/index.md#-151459758%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)) |
| [setConcentration](../-toggle-molecule-randomly/index.md#-330064727%2FFunctions%2F-267951372) | [jvm]<br>fun [setConcentration](../-toggle-molecule-randomly/index.md#-330064727%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), p1: [T](index.md)) |
| [target](../-abstract-steering-action-with-target/target.md) | [jvm]<br>open override fun [target](../-abstract-steering-action-with-target/target.md)(): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)<br>The position the owner of this action moves towards, in absolute coordinates. |
| [toString](../-abstract-action/to-string.md) | [jvm]<br>open override fun [toString](../-abstract-action/to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

## Properties

| Name | Summary |
|---|---|
| [maxWalk](index.md#843319539%2FProperties%2F-267951372) | [jvm]<br>open val [maxWalk](index.md#843319539%2FProperties%2F-267951372): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The maximum distance the pedestrian can walk, this is a length. |

//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[CognitiveAgentFollowLayer](index.md)

# CognitiveAgentFollowLayer

[jvm]\
open class [CognitiveAgentFollowLayer](index.md)(**env**: [Euclidean2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment/index.md)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>, **reaction**: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>, **pedestrian**: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.md)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>, **targetMolecule**: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)) : [AbstractLayerAction](../-abstract-layer-action/index.md)

Move the pedestrian towards positions of the environment with a high concentration of the target molecule.

## Parameters

jvm

| | |
|---|---|
| env | the environment inside which the pedestrian moves. |
| reaction | the reaction which executes this action. |
| pedestrian | the owner of this action. |
| targetMolecule | the {@link Molecule} you want to know the concentration in the different positions of the environment. |

## Constructors

| | |
|---|---|
| [CognitiveAgentFollowLayer](-cognitive-agent-follow-layer.md) | [jvm]<br>fun [CognitiveAgentFollowLayer](-cognitive-agent-follow-layer.md)(env: [Euclidean2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment/index.md)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>, pedestrian: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.md)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>, targetMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md))<br>    the environment inside which the pedestrian moves. |

## Functions

| Name | Summary |
|---|---|
| [cloneAction](index.md#2062987790%2FFunctions%2F-267951372) | [jvm]<br>open override fun [cloneAction](index.md#2062987790%2FFunctions%2F-267951372)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.md)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)> |
| [declareDependencyTo](../-camera-see/index.md#1970369254%2FFunctions%2F-267951372) | [jvm]<br>fun [declareDependencyTo](../-camera-see/index.md#1970369254%2FFunctions%2F-267951372)(p0: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)) |
| [execute](../-abstract-move-node/execute.md) | [jvm]<br>open override fun [execute](../-abstract-move-node/execute.md)() |
| [getConcentration](../-camera-see/index.md#-1328510210%2FFunctions%2F-267951372) | [jvm]<br>fun [getConcentration](../-camera-see/index.md#-1328510210%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)> |
| [getContext](../-abstract-move-node/get-context.md) | [jvm]<br>override fun [getContext](../-abstract-move-node/get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getCurrentPosition](../-levy-walk/index.md#1706811851%2FFunctions%2F-267951372) | [jvm]<br>fun [getCurrentPosition](../-levy-walk/index.md#1706811851%2FFunctions%2F-267951372)(): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md) |
| [getEnvironment](../-levy-walk/index.md#-391547238%2FFunctions%2F-267951372) | [jvm]<br>open fun [getEnvironment](../-levy-walk/index.md#-391547238%2FFunctions%2F-267951372)(): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)> |
| [getNextPosition](../-abstract-steering-action/get-next-position.md) | [jvm]<br>open override fun [getNextPosition](../-abstract-steering-action/get-next-position.md)(): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md) |
| [getNodePosition](index.md#-1319614241%2FFunctions%2F-267951372) | [jvm]<br>fun [getNodePosition](index.md#-1319614241%2FFunctions%2F-267951372)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md) | [jvm]<br>override fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [isAbsolute](../-levy-walk/index.md#9650230%2FFunctions%2F-267951372) | [jvm]<br>fun [isAbsolute](../-levy-walk/index.md#9650230%2FFunctions%2F-267951372)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [nextPosition](next-position.md) | [jvm]<br>open override fun [nextPosition](next-position.md)(): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)<br>The position the owner of this action moves to when it is executed, in relative coordinates with respect to its current position. |
| [nodeContains](../-camera-see/index.md#1662898740%2FFunctions%2F-267951372) | [jvm]<br>fun [nodeContains](../-camera-see/index.md#1662898740%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [removeConcentration](../-camera-see/index.md#-151459758%2FFunctions%2F-267951372) | [jvm]<br>fun [removeConcentration](../-camera-see/index.md#-151459758%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)) |
| [setConcentration](index.md#-1703683529%2FFunctions%2F-267951372) | [jvm]<br>fun [setConcentration](index.md#-1703683529%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), p1: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)) |
| [toString](../-abstract-action/to-string.md) | [jvm]<br>open override fun [toString](../-abstract-action/to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

## Properties

| Name | Summary |
|---|---|
| [maxWalk](index.md#1858618622%2FProperties%2F-267951372) | [jvm]<br>open val [maxWalk](index.md#1858618622%2FProperties%2F-267951372): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The maximum distance the pedestrian can walk, this is a length. |

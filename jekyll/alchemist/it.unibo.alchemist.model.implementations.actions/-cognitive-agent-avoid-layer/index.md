---
title: CognitiveAgentAvoidLayer
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[CognitiveAgentAvoidLayer](index.html)



# CognitiveAgentAvoidLayer



[jvm]\
class [CognitiveAgentAvoidLayer](index.html)@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()constructor(**environment**: [Euclidean2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment/index.html)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>, **reaction**: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>, **pedestrian**: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.html)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>, **targetMolecule**: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), **viewDepth**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [AbstractLayerAction](../-abstract-layer-action/index.html)

Move the pedestrian towards positions of the environment with a low concentration of the target molecule.



## Parameters


jvm

| | |
|---|---|
| environment | the environment inside which the pedestrian moves. |
| reaction | the reaction which executes this action. |
| pedestrian | the owner of this action. |
| targetMolecule | the {@link Molecule} you want to know the concentration in the different positions of the environment. |
| viewDepth | the depth of view of the pedestrian, defaults to infinity. |



## Constructors


| | |
|---|---|
| [CognitiveAgentAvoidLayer](-cognitive-agent-avoid-layer.html) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun [CognitiveAgentAvoidLayer](-cognitive-agent-avoid-layer.html)(environment: [Euclidean2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment/index.html)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>, pedestrian: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.html)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>, targetMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), viewDepth: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = Double.POSITIVE_INFINITY)<br>    the environment inside which the pedestrian moves. |


## Functions


| Name | Summary |
|---|---|
| [cloneAction](../-cognitive-agent-follow-layer/index.html#2062987790%2FFunctions%2F-134779887) | [jvm]<br>open override fun [cloneAction](../-cognitive-agent-follow-layer/index.html#2062987790%2FFunctions%2F-134779887)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)> |
| [declareDependencyTo](../-camera-see/index.html#1970369254%2FFunctions%2F-134779887) | [jvm]<br>fun [declareDependencyTo](../-camera-see/index.html#1970369254%2FFunctions%2F-134779887)(p0: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)) |
| [execute](../-abstract-move-node/execute.html) | [jvm]<br>open override fun [execute](../-abstract-move-node/execute.html)() |
| [getConcentration](../-camera-see/index.html#-1328510210%2FFunctions%2F-134779887) | [jvm]<br>fun [getConcentration](../-camera-see/index.html#-1328510210%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)> |
| [getContext](../-abstract-move-node/get-context.html) | [jvm]<br>override fun [getContext](../-abstract-move-node/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getCurrentPosition](../-levy-walk/index.html#1706811851%2FFunctions%2F-134779887) | [jvm]<br>fun [getCurrentPosition](../-levy-walk/index.html#1706811851%2FFunctions%2F-134779887)(): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html) |
| [getEnvironment](../-levy-walk/index.html#-391547238%2FFunctions%2F-134779887) | [jvm]<br>open fun [getEnvironment](../-levy-walk/index.html#-391547238%2FFunctions%2F-134779887)(): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)> |
| [getNextPosition](../-abstract-steering-action/get-next-position.html) | [jvm]<br>open override fun [getNextPosition](../-abstract-steering-action/get-next-position.html)(): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html) |
| [getNodePosition](../-cognitive-agent-follow-layer/index.html#-1319614241%2FFunctions%2F-134779887) | [jvm]<br>fun [getNodePosition](../-cognitive-agent-follow-layer/index.html#-1319614241%2FFunctions%2F-134779887)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html) | [jvm]<br>override fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [isAbsolute](../-levy-walk/index.html#9650230%2FFunctions%2F-134779887) | [jvm]<br>fun [isAbsolute](../-levy-walk/index.html#9650230%2FFunctions%2F-134779887)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [nextPosition](next-position.html) | [jvm]<br>open override fun [nextPosition](next-position.html)(): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html) |
| [nodeContains](../-camera-see/index.html#1662898740%2FFunctions%2F-134779887) | [jvm]<br>fun [nodeContains](../-camera-see/index.html#1662898740%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [removeConcentration](../-camera-see/index.html#-151459758%2FFunctions%2F-134779887) | [jvm]<br>fun [removeConcentration](../-camera-see/index.html#-151459758%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)) |
| [setConcentration](../-cognitive-agent-follow-layer/index.html#-1703683529%2FFunctions%2F-134779887) | [jvm]<br>fun [setConcentration](../-cognitive-agent-follow-layer/index.html#-1703683529%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), p1: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)) |
| [toString](../-abstract-action/to-string.html) | [jvm]<br>open override fun [toString](../-abstract-action/to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |


## Properties


| Name | Summary |
|---|---|
| [maxWalk](index.html#708400164%2FProperties%2F-134779887) | [jvm]<br>open val [maxWalk](index.html#708400164%2FProperties%2F-134779887): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The maximum distance the pedestrian can walk, this is a length. |


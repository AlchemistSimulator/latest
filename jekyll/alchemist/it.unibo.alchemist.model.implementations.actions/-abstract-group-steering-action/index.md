---
title: AbstractGroupSteeringAction
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[AbstractGroupSteeringAction](index.html)



# AbstractGroupSteeringAction



[jvm]\
abstract class [AbstractGroupSteeringAction](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[P](index.html)>>(**env**: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](index.html)>, **reaction**: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>, **pedestrian**: [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.html)<[T](index.html), [P](index.html), [A](index.html)>) : [AbstractSteeringAction](../-abstract-steering-action/index.html)<[T](index.html), [P](index.html), [A](index.html)> , [GroupSteeringAction](../../it.unibo.alchemist.model.interfaces/-group-steering-action/index.html)<[T](index.html), [P](index.html)> 

An abstract [GroupSteeringAction](../../it.unibo.alchemist.model.interfaces/-group-steering-action/index.html).



## Constructors


| | |
|---|---|
| [AbstractGroupSteeringAction](-abstract-group-steering-action.html) | [jvm]<br>fun <[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[P](index.html)>> [AbstractGroupSteeringAction](-abstract-group-steering-action.html)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>, pedestrian: [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.html)<[T](index.html), [P](index.html), [A](index.html)>) |


## Functions


| Name | Summary |
|---|---|
| [cloneAction](../-abstract-steering-action/clone-action.html) | [jvm]<br>open override fun [cloneAction](../-abstract-steering-action/clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](index.html)> |
| [declareDependencyTo](../-camera-see/index.html#1970369254%2FFunctions%2F-134779887) | [jvm]<br>fun [declareDependencyTo](../-camera-see/index.html#1970369254%2FFunctions%2F-134779887)(p0: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)) |
| [execute](../-abstract-move-node/execute.html) | [jvm]<br>open override fun [execute](../-abstract-move-node/execute.html)() |
| [getConcentration](../-camera-see/index.html#-1328510210%2FFunctions%2F-134779887) | [jvm]<br>fun [getConcentration](../-camera-see/index.html#-1328510210%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[T](index.html)> |
| [getContext](../-abstract-move-node/get-context.html) | [jvm]<br>override fun [getContext](../-abstract-move-node/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getCurrentPosition](../-levy-walk/index.html#1706811851%2FFunctions%2F-134779887) | [jvm]<br>fun [getCurrentPosition](../-levy-walk/index.html#1706811851%2FFunctions%2F-134779887)(): [P](index.html) |
| [getEnvironment](../-levy-walk/index.html#-391547238%2FFunctions%2F-134779887) | [jvm]<br>open fun [getEnvironment](../-levy-walk/index.html#-391547238%2FFunctions%2F-134779887)(): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](index.html)> |
| [getNextPosition](../-abstract-steering-action/get-next-position.html) | [jvm]<br>open override fun [getNextPosition](../-abstract-steering-action/get-next-position.html)(): [P](index.html) |
| [getNodePosition](../-levy-walk/index.html#1299827309%2FFunctions%2F-134779887) | [jvm]<br>fun [getNodePosition](../-levy-walk/index.html#1299827309%2FFunctions%2F-134779887)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>): [P](index.html) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html) | [jvm]<br>override fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [group](../../it.unibo.alchemist.model.interfaces/-group-steering-action/group.html) | [jvm]<br>abstract fun [group](../../it.unibo.alchemist.model.interfaces/-group-steering-action/group.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.html)<[T](index.html), [P](index.html), *>><br>The list of pedestrians influencing this action. |
| [isAbsolute](../-levy-walk/index.html#9650230%2FFunctions%2F-134779887) | [jvm]<br>fun [isAbsolute](../-levy-walk/index.html#9650230%2FFunctions%2F-134779887)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [nextPosition](../../it.unibo.alchemist.model.interfaces/-steering-action/next-position.html) | [jvm]<br>abstract fun [nextPosition](../../it.unibo.alchemist.model.interfaces/-steering-action/next-position.html)(): [P](index.html)<br>The position the owner of this action moves to when it is executed, in relative coordinates with respect to its current position. |
| [nodeContains](../-camera-see/index.html#1662898740%2FFunctions%2F-134779887) | [jvm]<br>fun [nodeContains](../-camera-see/index.html#1662898740%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [removeConcentration](../-camera-see/index.html#-151459758%2FFunctions%2F-134779887) | [jvm]<br>fun [removeConcentration](../-camera-see/index.html#-151459758%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)) |
| [setConcentration](../-toggle-molecule-randomly/index.html#-330064727%2FFunctions%2F-134779887) | [jvm]<br>fun [setConcentration](../-toggle-molecule-randomly/index.html#-330064727%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), p1: [T](index.html)) |
| [toString](../-abstract-action/to-string.html) | [jvm]<br>open override fun [toString](../-abstract-action/to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |


## Properties


| Name | Summary |
|---|---|
| [maxWalk](index.html#-1177106353%2FProperties%2F-134779887) | [jvm]<br>open val [maxWalk](index.html#-1177106353%2FProperties%2F-134779887): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The maximum distance the pedestrian can walk, this is a length. |


## Inheritors


| Name |
|---|
| [CognitiveAgentCohesion](../-cognitive-agent-cohesion/index.html) |
| [CognitiveAgentSeparation](../-cognitive-agent-separation/index.html) |


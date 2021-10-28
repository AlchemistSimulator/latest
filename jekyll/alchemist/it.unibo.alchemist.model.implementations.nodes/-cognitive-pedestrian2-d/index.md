---
title: CognitivePedestrian2D
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.nodes](../index.html)/[CognitivePedestrian2D](index.html)



# CognitivePedestrian2D



[jvm]\
open class [CognitivePedestrian2D](index.html)<[T](index.html)>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()constructor(**environment**: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.html)<[T](index.html)>, **randomGenerator**: RandomGenerator, **age**: [Age](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-age/index.html), **gender**: [Gender](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-gender/index.html), **danger**: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)?, **group**: [PedestrianGroup2D](../../it.unibo.alchemist.model.interfaces/-pedestrian-group2-d/index.html)<[T](index.html)>?) : [AbstractCognitivePedestrian](../-abstract-cognitive-pedestrian/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html), [Euclidean2DShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-shape-factory/index.html)> , [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.html)<[T](index.html)> 

Implementation of a cognitive pedestrian in the Euclidean world.



## Parameters


jvm

| | |
|---|---|
| environment | the environment inside which this pedestrian moves. |
| randomGenerator | the simulation {@link RandomGenerator}. |
| age | the age of this pedestrian. |
| gender | the gender of this pedestrian |
| danger | the molecule associated to danger in the environment. |



## Constructors


| | |
|---|---|
| [CognitivePedestrian2D](-cognitive-pedestrian2-d.html) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun <[T](index.html)> [CognitivePedestrian2D](-cognitive-pedestrian2-d.html)(environment: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.html)<[T](index.html)>, randomGenerator: RandomGenerator, age: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), gender: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), danger: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)? = null, group: [PedestrianGroup2D](../../it.unibo.alchemist.model.interfaces/-pedestrian-group2-d/index.html)<[T](index.html)>? = null) |
| [CognitivePedestrian2D](-cognitive-pedestrian2-d.html) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun <[T](index.html)> [CognitivePedestrian2D](-cognitive-pedestrian2-d.html)(environment: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.html)<[T](index.html)>, randomGenerator: RandomGenerator, age: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), gender: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), danger: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)? = null, group: [PedestrianGroup2D](../../it.unibo.alchemist.model.interfaces/-pedestrian-group2-d/index.html)<[T](index.html)>? = null) |
| [CognitivePedestrian2D](-cognitive-pedestrian2-d.html) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun <[T](index.html)> [CognitivePedestrian2D](-cognitive-pedestrian2-d.html)(environment: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.html)<[T](index.html)>, randomGenerator: RandomGenerator, age: [Age](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-age/index.html), gender: [Gender](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-gender/index.html), danger: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)? = null, group: [PedestrianGroup2D](../../it.unibo.alchemist.model.interfaces/-pedestrian-group2-d/index.html)<[T](index.html)>? = null)<br>    the environment inside which this pedestrian moves. |


## Functions


| Name | Summary |
|---|---|
| [addReaction](../-homogeneous-physical-pedestrian2-d/index.html#-1914162920%2FFunctions%2F-134779887) | [jvm]<br>override fun [addReaction](../-homogeneous-physical-pedestrian2-d/index.html#-1914162920%2FFunctions%2F-134779887)(p0: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>) |
| [cloneNode](../-homogeneous-physical-pedestrian2-d/index.html#1410251741%2FFunctions%2F-134779887) | [jvm]<br>open override fun [cloneNode](../-homogeneous-physical-pedestrian2-d/index.html#1410251741%2FFunctions%2F-134779887)(p0: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [AbstractNode](../-abstract-node/index.html)<[T](index.html)> |
| [compareTo](../-homogeneous-physical-pedestrian2-d/index.html#-635306233%2FFunctions%2F-134779887) | [jvm]<br>operator override fun [compareTo](../-homogeneous-physical-pedestrian2-d/index.html#-635306233%2FFunctions%2F-134779887)(@NotNull()other: @NotNull()[Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [contains](../-homogeneous-physical-pedestrian2-d/index.html#-1500024274%2FFunctions%2F-134779887) | [jvm]<br>open operator override fun [contains](../-homogeneous-physical-pedestrian2-d/index.html#-1500024274%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [equals](../-homogeneous-physical-pedestrian2-d/index.html#1855273807%2FFunctions%2F-134779887) | [jvm]<br>operator override fun [equals](../-homogeneous-physical-pedestrian2-d/index.html#1855273807%2FFunctions%2F-134779887)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](../-homogeneous-physical-pedestrian2-d/index.html#1514566078%2FFunctions%2F-134779887) | [jvm]<br>override fun [forEach](../-homogeneous-physical-pedestrian2-d/index.html#1514566078%2FFunctions%2F-134779887)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>>) |
| [getConcentration](../-homogeneous-physical-pedestrian2-d/index.html#-989109866%2FFunctions%2F-134779887) | [jvm]<br>open override fun [getConcentration](../-homogeneous-physical-pedestrian2-d/index.html#-989109866%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [T](index.html) |
| [getContents](../-abstract-node/get-contents.html) | [jvm]<br>open override fun [getContents](../-abstract-node/get-contents.html)(): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), [T](index.html)> |
| [getId](../-homogeneous-physical-pedestrian2-d/index.html#2063123767%2FFunctions%2F-134779887) | [jvm]<br>override fun [getId](../-homogeneous-physical-pedestrian2-d/index.html#2063123767%2FFunctions%2F-134779887)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMoleculeCount](../-abstract-node/get-molecule-count.html) | [jvm]<br>open override fun [getMoleculeCount](../-abstract-node/get-molecule-count.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getReactions](../-homogeneous-physical-pedestrian2-d/index.html#-301186114%2FFunctions%2F-134779887) | [jvm]<br>override fun [getReactions](../-homogeneous-physical-pedestrian2-d/index.html#-301186114%2FFunctions%2F-134779887)(): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>> |
| [hashCode](../-abstract-node/hash-code.html) | [jvm]<br>override fun [hashCode](../-abstract-node/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [influencialPeople](../-abstract-cognitive-pedestrian/influencial-people.html) | [jvm]<br>open override fun [influencialPeople](../-abstract-cognitive-pedestrian/influencial-people.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[CognitiveAgent](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-agent/index.html)><br>A list of all the cognitive agents who exert an influence on this cognitive agent. |
| [iterator](../-abstract-node/iterator.html) | [jvm]<br>operator override fun [iterator](../-abstract-node/iterator.html)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>> |
| [probabilityOfHelping](../-cognitive-physical-pedestrian2-d/index.html#-1298149345%2FFunctions%2F-134779887) | [jvm]<br>open override fun [probabilityOfHelping](../-cognitive-physical-pedestrian2-d/index.html#-1298149345%2FFunctions%2F-134779887)(toHelp: [HeterogeneousPedestrian](../../it.unibo.alchemist.model.interfaces/-heterogeneous-pedestrian/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html)>): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Value between 0 and 1 representing the probability this pedestrian will help another pedestrian in difficulty. |
| [removeConcentration](../-homogeneous-physical-pedestrian2-d/index.html#571173562%2FFunctions%2F-134779887) | [jvm]<br>open override fun [removeConcentration](../-homogeneous-physical-pedestrian2-d/index.html#571173562%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)) |
| [removeReaction](../-homogeneous-physical-pedestrian2-d/index.html#982079025%2FFunctions%2F-134779887) | [jvm]<br>override fun [removeReaction](../-homogeneous-physical-pedestrian2-d/index.html#982079025%2FFunctions%2F-134779887)(p0: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>) |
| [setConcentration](../-homogeneous-physical-pedestrian2-d/index.html#-1479666879%2FFunctions%2F-134779887) | [jvm]<br>open override fun [setConcentration](../-homogeneous-physical-pedestrian2-d/index.html#-1479666879%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), p1: [T](index.html)) |
| [speed](../-abstract-cognitive-pedestrian/speed.html) | [jvm]<br>open override fun [speed](../-abstract-cognitive-pedestrian/speed.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The speed at which the pedestrian is moving. |
| [spliterator](../-abstract-node/spliterator.html) | [jvm]<br>override fun [spliterator](../-abstract-node/spliterator.html)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>> |
| [toString](../-abstract-node/to-string.html) | [jvm]<br>open override fun [toString](../-abstract-node/to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [wantsToEscape](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-agent/wants-to-escape.html) | [jvm]<br>open fun [wantsToEscape](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-agent/wants-to-escape.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Whether or not this pedestrian intends to escape. |


## Properties


| Name | Summary |
|---|---|
| [age](index.html#1766013478%2FProperties%2F-134779887) | [jvm]<br>override val [age](index.html#1766013478%2FProperties%2F-134779887): [Age](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-age/index.html)<br>    the age of this pedestrian. |
| [cognitive](index.html#-429231061%2FProperties%2F-134779887) | [jvm]<br>open override val [cognitive](index.html#-429231061%2FProperties%2F-134779887): [CognitiveModel](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-model/index.html)<br>The cognitive model this agent adheres to. |
| [compliance](index.html#561056890%2FProperties%2F-134779887) | [jvm]<br>override val [compliance](index.html#561056890%2FProperties%2F-134779887): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Value between 0 and 1 representing the attitude towards conforming to social rules of this pedestrian. |
| [danger](index.html#-448398478%2FProperties%2F-134779887) | [jvm]<br>val [danger](index.html#-448398478%2FProperties%2F-134779887): [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)?<br>    the molecule associated to danger in the environment. |
| [environment](environment.html) | [jvm]<br>override val [environment](environment.html): [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.html)<[T](index.html)><br>    the environment inside which this pedestrian moves. |
| [fieldOfView](field-of-view.html) | [jvm]<br>override val [fieldOfView](field-of-view.html): [FieldOfView2D](../../it.unibo.alchemist.model.implementations.geometry.euclidean2d/-field-of-view2-d/index.html)<[T](index.html)><br>The field of view of a pedestrian in the Euclidean world. |
| [gender](index.html#1413475476%2FProperties%2F-134779887) | [jvm]<br>override val [gender](index.html#1413475476%2FProperties%2F-134779887): [Gender](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-gender/index.html)<br>    the gender of this pedestrian |
| [membershipGroup](index.html#-1882875364%2FProperties%2F-134779887) | [jvm]<br>open override val [membershipGroup](index.html#-1882875364%2FProperties%2F-134779887): [PedestrianGroup](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html)><br>The group this pedestrian belongs to. |
| [shape](shape.html) | [jvm]<br>open override val [shape](shape.html): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html)><br>The shape of any pedestrian in the Euclidean world. |


## Inheritors


| Name |
|---|
| [CognitivePhysicalPedestrian2D](../-cognitive-physical-pedestrian2-d/index.html) |


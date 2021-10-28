---
title: AbstractCognitivePedestrian
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.nodes](../index.html)/[AbstractCognitivePedestrian](index.html)



# AbstractCognitivePedestrian



[jvm]\
abstract class [AbstractCognitivePedestrian](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[P](index.html)>, [F](index.html) : [GeometricShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/index.html)<[P](index.html), [A](index.html)>>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()constructor(**environment**: [PhysicsEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment/index.html)<[T](index.html), [P](index.html), [A](index.html), [F](index.html)>, **randomGenerator**: RandomGenerator, **age**: [Age](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-age/index.html), **gender**: [Gender](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-gender/index.html), **danger**: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)?, **group**: [PedestrianGroup](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.html)<[T](index.html), [P](index.html), [A](index.html)>?, **cognitive**: [CognitiveModel](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-model/index.html)?) : [AbstractHeterogeneousPedestrian](../-abstract-heterogeneous-pedestrian/index.html)<[T](index.html), [P](index.html), [A](index.html), [F](index.html)> , [CognitivePedestrian](../../it.unibo.alchemist.model.interfaces/-cognitive-pedestrian/index.html)<[T](index.html), [P](index.html), [A](index.html)> 

Implementation of a cognitive pedestrian.



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
| [AbstractCognitivePedestrian](-abstract-cognitive-pedestrian.html) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun <[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[P](index.html)>, [F](index.html) : [GeometricShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/index.html)<[P](index.html), [A](index.html)>> [AbstractCognitivePedestrian](-abstract-cognitive-pedestrian.html)(environment: [PhysicsEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment/index.html)<[T](index.html), [P](index.html), [A](index.html), [F](index.html)>, randomGenerator: RandomGenerator, age: [Age](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-age/index.html), gender: [Gender](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-gender/index.html), danger: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)? = null, group: [PedestrianGroup](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.html)<[T](index.html), [P](index.html), [A](index.html)>? = null, cognitive: [CognitiveModel](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-model/index.html)? = null)<br>    the environment inside which this pedestrian moves. |


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
| [influencialPeople](influencial-people.html) | [jvm]<br>open override fun [influencialPeople](influencial-people.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[CognitiveAgent](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-agent/index.html)><br>A list of all the cognitive agents who exert an influence on this cognitive agent. |
| [iterator](../-abstract-node/iterator.html) | [jvm]<br>operator override fun [iterator](../-abstract-node/iterator.html)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>> |
| [probabilityOfHelping](index.html#2095044551%2FFunctions%2F-134779887) | [jvm]<br>open override fun [probabilityOfHelping](index.html#2095044551%2FFunctions%2F-134779887)(toHelp: [HeterogeneousPedestrian](../../it.unibo.alchemist.model.interfaces/-heterogeneous-pedestrian/index.html)<[T](index.html), [P](index.html), [A](index.html)>): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Value between 0 and 1 representing the probability this pedestrian will help another pedestrian in difficulty. |
| [removeConcentration](../-homogeneous-physical-pedestrian2-d/index.html#571173562%2FFunctions%2F-134779887) | [jvm]<br>open override fun [removeConcentration](../-homogeneous-physical-pedestrian2-d/index.html#571173562%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)) |
| [removeReaction](../-homogeneous-physical-pedestrian2-d/index.html#982079025%2FFunctions%2F-134779887) | [jvm]<br>override fun [removeReaction](../-homogeneous-physical-pedestrian2-d/index.html#982079025%2FFunctions%2F-134779887)(p0: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>) |
| [setConcentration](../-homogeneous-physical-pedestrian2-d/index.html#-1479666879%2FFunctions%2F-134779887) | [jvm]<br>open override fun [setConcentration](../-homogeneous-physical-pedestrian2-d/index.html#-1479666879%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), p1: [T](index.html)) |
| [speed](speed.html) | [jvm]<br>open override fun [speed](speed.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The speed at which the pedestrian is moving. |
| [spliterator](../-abstract-node/spliterator.html) | [jvm]<br>override fun [spliterator](../-abstract-node/spliterator.html)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>> |
| [toString](../-abstract-node/to-string.html) | [jvm]<br>open override fun [toString](../-abstract-node/to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [wantsToEscape](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-agent/wants-to-escape.html) | [jvm]<br>open fun [wantsToEscape](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-agent/wants-to-escape.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Whether or not this pedestrian intends to escape. |


## Properties


| Name | Summary |
|---|---|
| [age](index.html#-1432359366%2FProperties%2F-134779887) | [jvm]<br>override val [age](index.html#-1432359366%2FProperties%2F-134779887): [Age](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-age/index.html)<br>    the age of this pedestrian. |
| [cognitive](cognitive.html) | [jvm]<br>open override val [cognitive](cognitive.html): [CognitiveModel](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-model/index.html)<br>The cognitive model this agent adheres to. |
| [compliance](index.html#1371101670%2FProperties%2F-134779887) | [jvm]<br>override val [compliance](index.html#1371101670%2FProperties%2F-134779887): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Value between 0 and 1 representing the attitude towards conforming to social rules of this pedestrian. |
| [danger](danger.html) | [jvm]<br>val [danger](danger.html): [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)? = null<br>    the molecule associated to danger in the environment. |
| [environment](index.html#-284526682%2FProperties%2F-134779887) | [jvm]<br>open val [environment](index.html#-284526682%2FProperties%2F-134779887): [PhysicsEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment/index.html)<[T](index.html), [P](index.html), [A](index.html), [F](index.html)><br>    the environment inside which this pedestrian moves. |
| [gender](index.html#-1757425664%2FProperties%2F-134779887) | [jvm]<br>override val [gender](index.html#-1757425664%2FProperties%2F-134779887): [Gender](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-gender/index.html)<br>    the gender of this pedestrian |
| [membershipGroup](index.html#1777389616%2FProperties%2F-134779887) | [jvm]<br>open override val [membershipGroup](index.html#1777389616%2FProperties%2F-134779887): [PedestrianGroup](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.html)<[T](index.html), [P](index.html), [A](index.html)><br>The group this pedestrian belongs to. |
| [shape](index.html#-635684136%2FProperties%2F-134779887) | [jvm]<br>abstract val [shape](index.html#-635684136%2FProperties%2F-134779887): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.html)<[P](index.html), [A](index.html)> |


## Inheritors


| Name |
|---|
| [CognitivePedestrian2D](../-cognitive-pedestrian2-d/index.html) |


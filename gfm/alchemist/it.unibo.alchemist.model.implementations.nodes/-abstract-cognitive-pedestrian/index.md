//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.nodes](../index.md)/[AbstractCognitivePedestrian](index.md)

# AbstractCognitivePedestrian

[jvm]\
abstract class [AbstractCognitivePedestrian](index.md)<[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[P](index.md)>, [F](index.md) : [GeometricShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/index.md)<[P](index.md), [A](index.md)>>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()constructor(**environment**: [PhysicsEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment/index.md)<[T](index.md), [P](index.md), [A](index.md), [F](index.md)>, **randomGenerator**: RandomGenerator, **age**: [Age](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-age/index.md), **gender**: [Gender](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-gender/index.md), **danger**: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)?, **group**: [PedestrianGroup](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.md)<[T](index.md), [P](index.md), [A](index.md)>?, **cognitive**: [CognitiveModel](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-model/index.md)?) : [AbstractHeterogeneousPedestrian](../-abstract-heterogeneous-pedestrian/index.md)<[T](index.md), [P](index.md), [A](index.md), [F](index.md)> , [CognitivePedestrian](../../it.unibo.alchemist.model.interfaces/-cognitive-pedestrian/index.md)<[T](index.md), [P](index.md), [A](index.md)> 

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
| [AbstractCognitivePedestrian](-abstract-cognitive-pedestrian.md) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun <[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[P](index.md)>, [F](index.md) : [GeometricShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/index.md)<[P](index.md), [A](index.md)>> [AbstractCognitivePedestrian](-abstract-cognitive-pedestrian.md)(environment: [PhysicsEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment/index.md)<[T](index.md), [P](index.md), [A](index.md), [F](index.md)>, randomGenerator: RandomGenerator, age: [Age](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-age/index.md), gender: [Gender](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-gender/index.md), danger: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)? = null, group: [PedestrianGroup](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.md)<[T](index.md), [P](index.md), [A](index.md)>? = null, cognitive: [CognitiveModel](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-model/index.md)? = null)<br>    the environment inside which this pedestrian moves. |

## Functions

| Name | Summary |
|---|---|
| [addReaction](../-homogeneous-physical-pedestrian2-d/index.md#-1914162920%2FFunctions%2F-267951372) | [jvm]<br>override fun [addReaction](../-homogeneous-physical-pedestrian2-d/index.md#-1914162920%2FFunctions%2F-267951372)(p0: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>) |
| [cloneNode](../-homogeneous-physical-pedestrian2-d/index.md#1410251741%2FFunctions%2F-267951372) | [jvm]<br>open override fun [cloneNode](../-homogeneous-physical-pedestrian2-d/index.md#1410251741%2FFunctions%2F-267951372)(p0: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [AbstractNode](../-abstract-node/index.md)<[T](index.md)> |
| [compareTo](../-homogeneous-physical-pedestrian2-d/index.md#-635306233%2FFunctions%2F-267951372) | [jvm]<br>operator override fun [compareTo](../-homogeneous-physical-pedestrian2-d/index.md#-635306233%2FFunctions%2F-267951372)(@NotNull()other: @NotNull()[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [contains](../-homogeneous-physical-pedestrian2-d/index.md#-1500024274%2FFunctions%2F-267951372) | [jvm]<br>open operator override fun [contains](../-homogeneous-physical-pedestrian2-d/index.md#-1500024274%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [equals](../-homogeneous-physical-pedestrian2-d/index.md#1855273807%2FFunctions%2F-267951372) | [jvm]<br>operator override fun [equals](../-homogeneous-physical-pedestrian2-d/index.md#1855273807%2FFunctions%2F-267951372)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](../-homogeneous-physical-pedestrian2-d/index.md#1514566078%2FFunctions%2F-267951372) | [jvm]<br>override fun [forEach](../-homogeneous-physical-pedestrian2-d/index.md#1514566078%2FFunctions%2F-267951372)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>>) |
| [getConcentration](../-homogeneous-physical-pedestrian2-d/index.md#-989109866%2FFunctions%2F-267951372) | [jvm]<br>open override fun [getConcentration](../-homogeneous-physical-pedestrian2-d/index.md#-989109866%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [T](index.md) |
| [getContents](../-abstract-node/get-contents.md) | [jvm]<br>open override fun [getContents](../-abstract-node/get-contents.md)(): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), [T](index.md)> |
| [getId](../-homogeneous-physical-pedestrian2-d/index.md#2063123767%2FFunctions%2F-267951372) | [jvm]<br>override fun [getId](../-homogeneous-physical-pedestrian2-d/index.md#2063123767%2FFunctions%2F-267951372)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMoleculeCount](../-abstract-node/get-molecule-count.md) | [jvm]<br>open override fun [getMoleculeCount](../-abstract-node/get-molecule-count.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getReactions](../-homogeneous-physical-pedestrian2-d/index.md#-301186114%2FFunctions%2F-267951372) | [jvm]<br>override fun [getReactions](../-homogeneous-physical-pedestrian2-d/index.md#-301186114%2FFunctions%2F-267951372)(): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>> |
| [hashCode](../-abstract-node/hash-code.md) | [jvm]<br>override fun [hashCode](../-abstract-node/hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [influencialPeople](influencial-people.md) | [jvm]<br>open override fun [influencialPeople](influencial-people.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[CognitiveAgent](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-agent/index.md)><br>A list of all the cognitive agents who exert an influence on this cognitive agent. |
| [iterator](../-abstract-node/iterator.md) | [jvm]<br>operator override fun [iterator](../-abstract-node/iterator.md)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>> |
| [probabilityOfHelping](index.md#2095044551%2FFunctions%2F-267951372) | [jvm]<br>open override fun [probabilityOfHelping](index.md#2095044551%2FFunctions%2F-267951372)(toHelp: [HeterogeneousPedestrian](../../it.unibo.alchemist.model.interfaces/-heterogeneous-pedestrian/index.md)<[T](index.md), [P](index.md), [A](index.md)>): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Value between 0 and 1 representing the probability this pedestrian will help another pedestrian in difficulty. |
| [removeConcentration](../-homogeneous-physical-pedestrian2-d/index.md#571173562%2FFunctions%2F-267951372) | [jvm]<br>open override fun [removeConcentration](../-homogeneous-physical-pedestrian2-d/index.md#571173562%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)) |
| [removeReaction](../-homogeneous-physical-pedestrian2-d/index.md#982079025%2FFunctions%2F-267951372) | [jvm]<br>override fun [removeReaction](../-homogeneous-physical-pedestrian2-d/index.md#982079025%2FFunctions%2F-267951372)(p0: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>) |
| [setConcentration](../-homogeneous-physical-pedestrian2-d/index.md#-1479666879%2FFunctions%2F-267951372) | [jvm]<br>open override fun [setConcentration](../-homogeneous-physical-pedestrian2-d/index.md#-1479666879%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), p1: [T](index.md)) |
| [speed](speed.md) | [jvm]<br>open override fun [speed](speed.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The speed at which the pedestrian is moving. |
| [spliterator](../-abstract-node/spliterator.md) | [jvm]<br>override fun [spliterator](../-abstract-node/spliterator.md)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>> |
| [toString](../-abstract-node/to-string.md) | [jvm]<br>open override fun [toString](../-abstract-node/to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [wantsToEscape](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-agent/wants-to-escape.md) | [jvm]<br>open fun [wantsToEscape](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-agent/wants-to-escape.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Whether or not this pedestrian intends to escape. |

## Properties

| Name | Summary |
|---|---|
| [age](index.md#-1432359366%2FProperties%2F-267951372) | [jvm]<br>override val [age](index.md#-1432359366%2FProperties%2F-267951372): [Age](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-age/index.md)<br>    the age of this pedestrian. |
| [cognitive](cognitive.md) | [jvm]<br>open override val [cognitive](cognitive.md): [CognitiveModel](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-model/index.md)<br>The cognitive model this agent adheres to. |
| [compliance](index.md#1371101670%2FProperties%2F-267951372) | [jvm]<br>override val [compliance](index.md#1371101670%2FProperties%2F-267951372): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Value between 0 and 1 representing the attitude towards conforming to social rules of this pedestrian. |
| [danger](danger.md) | [jvm]<br>val [danger](danger.md): [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)? = null<br>    the molecule associated to danger in the environment. |
| [environment](index.md#-284526682%2FProperties%2F-267951372) | [jvm]<br>open val [environment](index.md#-284526682%2FProperties%2F-267951372): [PhysicsEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment/index.md)<[T](index.md), [P](index.md), [A](index.md), [F](index.md)><br>    the environment inside which this pedestrian moves. |
| [gender](index.md#-1757425664%2FProperties%2F-267951372) | [jvm]<br>override val [gender](index.md#-1757425664%2FProperties%2F-267951372): [Gender](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-gender/index.md)<br>    the gender of this pedestrian |
| [membershipGroup](index.md#1777389616%2FProperties%2F-267951372) | [jvm]<br>open override val [membershipGroup](index.md#1777389616%2FProperties%2F-267951372): [PedestrianGroup](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.md)<[T](index.md), [P](index.md), [A](index.md)><br>The group this pedestrian belongs to. |
| [shape](index.md#-635684136%2FProperties%2F-267951372) | [jvm]<br>abstract val [shape](index.md#-635684136%2FProperties%2F-267951372): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.md)<[P](index.md), [A](index.md)> |

## Inheritors

| Name |
|---|
| [CognitivePedestrian2D](../-cognitive-pedestrian2-d/index.md) |

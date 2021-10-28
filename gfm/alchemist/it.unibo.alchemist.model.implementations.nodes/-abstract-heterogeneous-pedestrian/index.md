//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.nodes](../index.md)/[AbstractHeterogeneousPedestrian](index.md)

# AbstractHeterogeneousPedestrian

[jvm]\
abstract class [AbstractHeterogeneousPedestrian](index.md)<[T](index.md), [P](index.md) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](index.md)>, [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[P](index.md)>, [F](index.md) : [GeometricShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/index.md)<[P](index.md), [A](index.md)>>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()constructor(**environment**: [PhysicsEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment/index.md)<[T](index.md), [P](index.md), [A](index.md), [F](index.md)>, **randomGenerator**: RandomGenerator, **age**: [Age](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-age/index.md), **gender**: [Gender](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-gender/index.md), **group**: [PedestrianGroup](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.md)<[T](index.md), [P](index.md), [A](index.md)>?) : [AbstractHomogeneousPedestrian](../-abstract-homogeneous-pedestrian/index.md)<[T](index.md), [P](index.md), [A](index.md), [F](index.md)> , [HeterogeneousPedestrian](../../it.unibo.alchemist.model.interfaces/-heterogeneous-pedestrian/index.md)<[T](index.md), [P](index.md), [A](index.md)> 

Implementation of a heterogeneous pedestrian.

## Parameters

jvm

| | |
|---|---|
| environment | the environment inside which this pedestrian moves. |
| randomGenerator | the simulation {@link RandomGenerator}. |
| age | the age of this pedestrian. |
| gender | the gender of this pedestrian |

## Constructors

| | |
|---|---|
| [AbstractHeterogeneousPedestrian](-abstract-heterogeneous-pedestrian.md) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun <[T](index.md), [P](index.md) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](index.md)>, [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[P](index.md)>, [F](index.md) : [GeometricShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/index.md)<[P](index.md), [A](index.md)>> [AbstractHeterogeneousPedestrian](-abstract-heterogeneous-pedestrian.md)(environment: [PhysicsEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment/index.md)<[T](index.md), [P](index.md), [A](index.md), [F](index.md)>, randomGenerator: RandomGenerator, age: [Age](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-age/index.md), gender: [Gender](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-gender/index.md), group: [PedestrianGroup](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.md)<[T](index.md), [P](index.md), [A](index.md)>? = null)<br>    the environment inside which this pedestrian moves. |

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
| [iterator](../-abstract-node/iterator.md) | [jvm]<br>operator override fun [iterator](../-abstract-node/iterator.md)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>> |
| [probabilityOfHelping](probability-of-helping.md) | [jvm]<br>open override fun [probabilityOfHelping](probability-of-helping.md)(toHelp: [HeterogeneousPedestrian](../../it.unibo.alchemist.model.interfaces/-heterogeneous-pedestrian/index.md)<[T](index.md), [P](index.md), [A](index.md)>): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Value between 0 and 1 representing the probability this pedestrian will help another pedestrian in difficulty. |
| [removeConcentration](../-homogeneous-physical-pedestrian2-d/index.md#571173562%2FFunctions%2F-267951372) | [jvm]<br>open override fun [removeConcentration](../-homogeneous-physical-pedestrian2-d/index.md#571173562%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)) |
| [removeReaction](../-homogeneous-physical-pedestrian2-d/index.md#982079025%2FFunctions%2F-267951372) | [jvm]<br>override fun [removeReaction](../-homogeneous-physical-pedestrian2-d/index.md#982079025%2FFunctions%2F-267951372)(p0: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>) |
| [setConcentration](../-homogeneous-physical-pedestrian2-d/index.md#-1479666879%2FFunctions%2F-267951372) | [jvm]<br>open override fun [setConcentration](../-homogeneous-physical-pedestrian2-d/index.md#-1479666879%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), p1: [T](index.md)) |
| [speed](../-abstract-homogeneous-pedestrian/speed.md) | [jvm]<br>open override fun [speed](../-abstract-homogeneous-pedestrian/speed.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The speed at which the pedestrian is moving. |
| [spliterator](../-abstract-node/spliterator.md) | [jvm]<br>override fun [spliterator](../-abstract-node/spliterator.md)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>> |
| [toString](../-abstract-node/to-string.md) | [jvm]<br>open override fun [toString](../-abstract-node/to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

## Properties

| Name | Summary |
|---|---|
| [age](age.md) | [jvm]<br>override val [age](age.md): [Age](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-age/index.md)<br>    the age of this pedestrian. |
| [compliance](compliance.md) | [jvm]<br>override val [compliance](compliance.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Value between 0 and 1 representing the attitude towards conforming to social rules of this pedestrian. |
| [environment](index.md#1614847187%2FProperties%2F-267951372) | [jvm]<br>open val [environment](index.md#1614847187%2FProperties%2F-267951372): [PhysicsEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment/index.md)<[T](index.md), [P](index.md), [A](index.md), [F](index.md)><br>    the environment inside which this pedestrian moves. |
| [gender](gender.md) | [jvm]<br>override val [gender](gender.md): [Gender](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-gender/index.md)<br>    the gender of this pedestrian |
| [membershipGroup](index.md#1543935709%2FProperties%2F-267951372) | [jvm]<br>open override val [membershipGroup](index.md#1543935709%2FProperties%2F-267951372): [PedestrianGroup](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.md)<[T](index.md), [P](index.md), [A](index.md)><br>The group this pedestrian belongs to. |
| [shape](index.md#-479394363%2FProperties%2F-267951372) | [jvm]<br>abstract val [shape](index.md#-479394363%2FProperties%2F-267951372): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.md)<[P](index.md), [A](index.md)> |

## Inheritors

| Name |
|---|
| [AbstractCognitivePedestrian](../-abstract-cognitive-pedestrian/index.md) |
| [HeterogeneousPedestrian2D](../-heterogeneous-pedestrian2-d/index.md) |

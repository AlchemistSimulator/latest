//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[PedestrianGroup](index.md)

# PedestrianGroup

[jvm]\
interface [PedestrianGroup](index.md)<[T](index.md), [P](index.md) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[P](index.md)>> : [Group](../-group/index.md)<[T](index.md), [Pedestrian](../-pedestrian/index.md)<[T](index.md), [P](index.md), [A](index.md)>> 

A [Group](../-group/index.md) of [Pedestrian](../-pedestrian/index.md)s.

## Functions

| Name | Summary |
|---|---|
| [addMember](index.md#-660227767%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [addMember](index.md#-660227767%2FFunctions%2F-267951372)(node: [Pedestrian](../-pedestrian/index.md)<[T](index.md), [P](index.md), [A](index.md)>): [Group](../-group/index.md)<[T](index.md), [Pedestrian](../-pedestrian/index.md)<[T](index.md), [P](index.md), [A](index.md)>><br>Add a node in this group if not already part of it. |
| [contains](index.md#-1711138971%2FFunctions%2F-267951372) | [jvm]<br>open fun [contains](index.md#-1711138971%2FFunctions%2F-267951372)(node: [Pedestrian](../-pedestrian/index.md)<[T](index.md), [P](index.md), [A](index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Whether a node belongs to this group or not. |
| [removeMember](index.md#623604262%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [removeMember](index.md#623604262%2FFunctions%2F-267951372)(node: [Pedestrian](../-pedestrian/index.md)<[T](index.md), [P](index.md), [A](index.md)>): [Group](../-group/index.md)<[T](index.md), [Pedestrian](../-pedestrian/index.md)<[T](index.md), [P](index.md), [A](index.md)>><br>Remove a node from this group. |

## Properties

| Name | Summary |
|---|---|
| [members](index.md#-20452785%2FProperties%2F-267951372) | [jvm]<br>abstract val [members](index.md#-20452785%2FProperties%2F-267951372): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Pedestrian](../-pedestrian/index.md)<[T](index.md), [P](index.md), [A](index.md)>><br>The list of pedestrians belonging to this group. |

## Inheritors

| Name |
|---|
| [Alone](../../it.unibo.alchemist.model.implementations.groups/-alone/index.md) |
| [PedestrianGroup2D](../-pedestrian-group2-d/index.md) |

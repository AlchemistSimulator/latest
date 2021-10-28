//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.groups](../index.md)/[Friends](index.md)

# Friends

[jvm]\
class [Friends](index.md)<[T](index.md), [S](index.md) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[S](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[S](index.md)>> : [GenericGroup](../-generic-group/index.md)<[T](index.md), [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.md)<[T](index.md), [S](index.md), [A](index.md)>> 

A generic, leaderless group of pedestrians.

## Constructors

| | |
|---|---|
| [Friends](-friends.md) | [jvm]<br>fun [Friends](-friends.md)() |

## Functions

| Name | Summary |
|---|---|
| [addMember](index.md#1984121863%2FFunctions%2F-267951372) | [jvm]<br>open override fun [addMember](index.md#1984121863%2FFunctions%2F-267951372)(node: [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.md)<[T](index.md), [S](index.md), [A](index.md)>): [Group](../../it.unibo.alchemist.model.interfaces/-group/index.md)<[T](index.md), [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.md)<[T](index.md), [S](index.md), [A](index.md)>><br>Add a node in this group if not already part of it. |
| [contains](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.md#-1711138971%2FFunctions%2F-267951372) | [jvm]<br>open fun [contains](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.md#-1711138971%2FFunctions%2F-267951372)(node: [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.md)<[T](index.md), [S](index.md), [A](index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Whether a node belongs to this group or not. |
| [removeMember](index.md#153288360%2FFunctions%2F-267951372) | [jvm]<br>open override fun [removeMember](index.md#153288360%2FFunctions%2F-267951372)(node: [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.md)<[T](index.md), [S](index.md), [A](index.md)>): [Group](../../it.unibo.alchemist.model.interfaces/-group/index.md)<[T](index.md), [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.md)<[T](index.md), [S](index.md), [A](index.md)>><br>Remove a node from this group. |

## Properties

| Name | Summary |
|---|---|
| [members](index.md#-317825225%2FProperties%2F-267951372) | [jvm]<br>open override val [members](index.md#-317825225%2FProperties%2F-267951372): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.md)<[T](index.md), [S](index.md), [A](index.md)>><br>The list of pedestrians belonging to this group. |

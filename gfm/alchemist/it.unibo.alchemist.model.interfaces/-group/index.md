//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Group](index.md)

# Group

[jvm]\
interface [Group](index.md)<[T](index.md), [N](index.md) : [Node](../-node/index.md)<[T](index.md)>>

A group of nodes.

## Functions

| Name | Summary |
|---|---|
| [addMember](add-member.md) | [jvm]<br>abstract fun [addMember](add-member.md)(node: [N](index.md)): [Group](index.md)<[T](index.md), [N](index.md)><br>Add a node in this group if not already part of it. |
| [contains](contains.md) | [jvm]<br>open fun [contains](contains.md)(node: [N](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Whether a node belongs to this group or not. |
| [removeMember](remove-member.md) | [jvm]<br>abstract fun [removeMember](remove-member.md)(node: [N](index.md)): [Group](index.md)<[T](index.md), [N](index.md)><br>Remove a node from this group. |

## Properties

| Name | Summary |
|---|---|
| [members](members.md) | [jvm]<br>abstract val [members](members.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[N](index.md)><br>The list of pedestrians belonging to this group. |

## Inheritors

| Name |
|---|
| [GenericGroup](../../it.unibo.alchemist.model.implementations.groups/-generic-group/index.md) |
| [GroupWithLeader](../-group-with-leader/index.md) |
| [PedestrianGroup](../-pedestrian-group/index.md) |

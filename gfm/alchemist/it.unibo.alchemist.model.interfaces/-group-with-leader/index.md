//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[GroupWithLeader](index.md)

# GroupWithLeader

[jvm]\
interface [GroupWithLeader](index.md)<[T](index.md), [N](index.md) : [Node](../-node/index.md)<[T](index.md)>> : [Group](../-group/index.md)<[T](index.md), [N](index.md)> 

A group with a special member acting as a leader.

## Functions

| Name | Summary |
|---|---|
| [addMember](../-group/add-member.md) | [jvm]<br>abstract fun [addMember](../-group/add-member.md)(node: [N](index.md)): [Group](../-group/index.md)<[T](index.md), [N](index.md)><br>Add a node in this group if not already part of it. |
| [contains](../-group/contains.md) | [jvm]<br>open fun [contains](../-group/contains.md)(node: [N](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Whether a node belongs to this group or not. |
| [removeMember](../-group/remove-member.md) | [jvm]<br>abstract fun [removeMember](../-group/remove-member.md)(node: [N](index.md)): [Group](../-group/index.md)<[T](index.md), [N](index.md)><br>Remove a node from this group. |

## Properties

| Name | Summary |
|---|---|
| [leader](leader.md) | [jvm]<br>abstract val [leader](leader.md): [N](index.md)<br>The leader of the group. |
| [members](index.md#-295318971%2FProperties%2F-267951372) | [jvm]<br>abstract val [members](index.md#-295318971%2FProperties%2F-267951372): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[N](index.md)><br>The list of pedestrians belonging to this group. |

## Inheritors

| Name |
|---|
| [Family](../../it.unibo.alchemist.model.implementations.groups/-family/index.md) |

//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.groups](../index.md)/[GenericGroup](index.md)

# GenericGroup

[jvm]\
open class [GenericGroup](index.md)<[T](index.md), [N](index.md) : [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>> : [Group](../../it.unibo.alchemist.model.interfaces/-group/index.md)<[T](index.md), [N](index.md)> 

Basic implementation of a group.

## Constructors

| | |
|---|---|
| [GenericGroup](-generic-group.md) | [jvm]<br>fun [GenericGroup](-generic-group.md)() |

## Functions

| Name | Summary |
|---|---|
| [addMember](add-member.md) | [jvm]<br>open override fun [addMember](add-member.md)(node: [N](index.md)): [Group](../../it.unibo.alchemist.model.interfaces/-group/index.md)<[T](index.md), [N](index.md)><br>Add a node in this group if not already part of it. |
| [contains](../../it.unibo.alchemist.model.interfaces/-group/contains.md) | [jvm]<br>open fun [contains](../../it.unibo.alchemist.model.interfaces/-group/contains.md)(node: [N](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Whether a node belongs to this group or not. |
| [removeMember](remove-member.md) | [jvm]<br>open override fun [removeMember](remove-member.md)(node: [N](index.md)): [Group](../../it.unibo.alchemist.model.interfaces/-group/index.md)<[T](index.md), [N](index.md)><br>Remove a node from this group. |

## Properties

| Name | Summary |
|---|---|
| [members](members.md) | [jvm]<br>open override val [members](members.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[N](index.md)><br>The list of pedestrians belonging to this group. |

## Inheritors

| Name |
|---|
| [Family](../-family/index.md) |
| [Friends](../-friends/index.md) |

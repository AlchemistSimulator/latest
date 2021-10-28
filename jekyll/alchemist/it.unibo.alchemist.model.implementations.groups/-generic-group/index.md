---
title: GenericGroup
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.groups](../index.html)/[GenericGroup](index.html)



# GenericGroup



[jvm]\
open class [GenericGroup](index.html)<[T](index.html), [N](index.html) : [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>> : [Group](../../it.unibo.alchemist.model.interfaces/-group/index.html)<[T](index.html), [N](index.html)> 

Basic implementation of a group.



## Constructors


| | |
|---|---|
| [GenericGroup](-generic-group.html) | [jvm]<br>fun [GenericGroup](-generic-group.html)() |


## Functions


| Name | Summary |
|---|---|
| [addMember](add-member.html) | [jvm]<br>open override fun [addMember](add-member.html)(node: [N](index.html)): [Group](../../it.unibo.alchemist.model.interfaces/-group/index.html)<[T](index.html), [N](index.html)><br>Add a node in this group if not already part of it. |
| [contains](../../it.unibo.alchemist.model.interfaces/-group/contains.html) | [jvm]<br>open fun [contains](../../it.unibo.alchemist.model.interfaces/-group/contains.html)(node: [N](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Whether a node belongs to this group or not. |
| [removeMember](remove-member.html) | [jvm]<br>open override fun [removeMember](remove-member.html)(node: [N](index.html)): [Group](../../it.unibo.alchemist.model.interfaces/-group/index.html)<[T](index.html), [N](index.html)><br>Remove a node from this group. |


## Properties


| Name | Summary |
|---|---|
| [members](members.html) | [jvm]<br>open override val [members](members.html): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[N](index.html)><br>The list of pedestrians belonging to this group. |


## Inheritors


| Name |
|---|
| [Family](../-family/index.html) |
| [Friends](../-friends/index.html) |


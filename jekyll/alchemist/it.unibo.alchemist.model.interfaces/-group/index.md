---
title: Group
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Group](index.html)



# Group



[jvm]\
interface [Group](index.html)<[T](index.html), [N](index.html) : [Node](../-node/index.html)<[T](index.html)>>

A group of nodes.



## Functions


| Name | Summary |
|---|---|
| [addMember](add-member.html) | [jvm]<br>abstract fun [addMember](add-member.html)(node: [N](index.html)): [Group](index.html)<[T](index.html), [N](index.html)><br>Add a node in this group if not already part of it. |
| [contains](contains.html) | [jvm]<br>open fun [contains](contains.html)(node: [N](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Whether a node belongs to this group or not. |
| [removeMember](remove-member.html) | [jvm]<br>abstract fun [removeMember](remove-member.html)(node: [N](index.html)): [Group](index.html)<[T](index.html), [N](index.html)><br>Remove a node from this group. |


## Properties


| Name | Summary |
|---|---|
| [members](members.html) | [jvm]<br>abstract val [members](members.html): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[N](index.html)><br>The list of pedestrians belonging to this group. |


## Inheritors


| Name |
|---|
| [GenericGroup](../../it.unibo.alchemist.model.implementations.groups/-generic-group/index.html) |
| [GroupWithLeader](../-group-with-leader/index.html) |
| [PedestrianGroup](../-pedestrian-group/index.html) |


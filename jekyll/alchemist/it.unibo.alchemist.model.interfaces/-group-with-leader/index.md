---
title: GroupWithLeader
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[GroupWithLeader](index.html)



# GroupWithLeader



[jvm]\
interface [GroupWithLeader](index.html)<[T](index.html), [N](index.html) : [Node](../-node/index.html)<[T](index.html)>> : [Group](../-group/index.html)<[T](index.html), [N](index.html)> 

A group with a special member acting as a leader.



## Functions


| Name | Summary |
|---|---|
| [addMember](../-group/add-member.html) | [jvm]<br>abstract fun [addMember](../-group/add-member.html)(node: [N](index.html)): [Group](../-group/index.html)<[T](index.html), [N](index.html)><br>Add a node in this group if not already part of it. |
| [contains](../-group/contains.html) | [jvm]<br>open fun [contains](../-group/contains.html)(node: [N](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Whether a node belongs to this group or not. |
| [removeMember](../-group/remove-member.html) | [jvm]<br>abstract fun [removeMember](../-group/remove-member.html)(node: [N](index.html)): [Group](../-group/index.html)<[T](index.html), [N](index.html)><br>Remove a node from this group. |


## Properties


| Name | Summary |
|---|---|
| [leader](leader.html) | [jvm]<br>abstract val [leader](leader.html): [N](index.html)<br>The leader of the group. |
| [members](index.html#-295318971%2FProperties%2F-134779887) | [jvm]<br>abstract val [members](index.html#-295318971%2FProperties%2F-134779887): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[N](index.html)><br>The list of pedestrians belonging to this group. |


## Inheritors


| Name |
|---|
| [Family](../../it.unibo.alchemist.model.implementations.groups/-family/index.html) |


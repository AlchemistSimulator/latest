---
title: Family
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.groups](../index.html)/[Family](index.html)



# Family



[jvm]\
class [Family](index.html)<[T](index.html), [S](index.html) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[S](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[S](index.html)>>(**comparator**: [Comparator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-comparator/index.html)<[Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.html)<[T](index.html), [S](index.html), [A](index.html)>>) : [GenericGroup](../-generic-group/index.html)<[T](index.html), [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.html)<[T](index.html), [S](index.html), [A](index.html)>> , [GroupWithLeader](../../it.unibo.alchemist.model.interfaces/-group-with-leader/index.html)<[T](index.html), [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.html)<[T](index.html), [S](index.html), [A](index.html)>> 

A [Family](index.html) is modeled as a group of pedestrians with a leader.



## Constructors


| | |
|---|---|
| [Family](-family.html) | [jvm]<br>fun [Family](-family.html)(comparator: [Comparator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-comparator/index.html)<[Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.html)<[T](index.html), [S](index.html), [A](index.html)>> = Comparator { a, b -> a.id.compareTo(b.id) }) |


## Functions


| Name | Summary |
|---|---|
| [addMember](../-friends/index.html#1984121863%2FFunctions%2F-134779887) | [jvm]<br>open override fun [addMember](../-friends/index.html#1984121863%2FFunctions%2F-134779887)(node: [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.html)<[T](index.html), [S](index.html), [A](index.html)>): [Group](../../it.unibo.alchemist.model.interfaces/-group/index.html)<[T](index.html), [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.html)<[T](index.html), [S](index.html), [A](index.html)>><br>Add a node in this group if not already part of it. |
| [contains](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.html#-1711138971%2FFunctions%2F-134779887) | [jvm]<br>open fun [contains](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.html#-1711138971%2FFunctions%2F-134779887)(node: [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.html)<[T](index.html), [S](index.html), [A](index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Whether a node belongs to this group or not. |
| [removeMember](../-friends/index.html#153288360%2FFunctions%2F-134779887) | [jvm]<br>open override fun [removeMember](../-friends/index.html#153288360%2FFunctions%2F-134779887)(node: [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.html)<[T](index.html), [S](index.html), [A](index.html)>): [Group](../../it.unibo.alchemist.model.interfaces/-group/index.html)<[T](index.html), [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.html)<[T](index.html), [S](index.html), [A](index.html)>><br>Remove a node from this group. |


## Properties


| Name | Summary |
|---|---|
| [leader](leader.html) | [jvm]<br>open override val [leader](leader.html): [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.html)<[T](index.html), [S](index.html), [A](index.html)><br>The leader of the group. |
| [members](index.html#1817275830%2FProperties%2F-134779887) | [jvm]<br>open override val [members](index.html#1817275830%2FProperties%2F-134779887): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.html)<[T](index.html), [S](index.html), [A](index.html)>><br>The list of pedestrians belonging to this group. |


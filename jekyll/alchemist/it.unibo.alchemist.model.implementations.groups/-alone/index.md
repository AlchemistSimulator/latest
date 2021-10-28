---
title: Alone
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.groups](../index.html)/[Alone](index.html)



# Alone



[jvm]\
class [Alone](index.html)<[T](index.html), [S](index.html) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[S](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[S](index.html)>>(**pedestrian**: [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.html)<[T](index.html), [S](index.html), [A](index.html)>) : [PedestrianGroup](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.html)<[T](index.html), [S](index.html), [A](index.html)> 

Group representing a pedestrian alone.



## Constructors


| | |
|---|---|
| [Alone](-alone.html) | [jvm]<br>fun <[T](index.html), [S](index.html) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[S](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[S](index.html)>> [Alone](-alone.html)(pedestrian: [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.html)<[T](index.html), [S](index.html), [A](index.html)>) |


## Functions


| Name | Summary |
|---|---|
| [addMember](add-member.html) | [jvm]<br>open override fun [addMember](add-member.html)(node: [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.html)<[T](index.html), [S](index.html), [A](index.html)>): [PedestrianGroup](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.html)<[T](index.html), [S](index.html), [A](index.html)><br>Add a node in this group if not already part of it. |
| [contains](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.html#-1711138971%2FFunctions%2F-134779887) | [jvm]<br>open fun [contains](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.html#-1711138971%2FFunctions%2F-134779887)(node: [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.html)<[T](index.html), [S](index.html), [A](index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Whether a node belongs to this group or not. |
| [removeMember](remove-member.html) | [jvm]<br>open override fun [removeMember](remove-member.html)(node: [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.html)<[T](index.html), [S](index.html), [A](index.html)>): [PedestrianGroup](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.html)<[T](index.html), [S](index.html), [A](index.html)><br>Remove a node from this group. |


## Properties


| Name | Summary |
|---|---|
| [members](members.html) | [jvm]<br>open override val [members](members.html): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.html)<[T](index.html), [S](index.html), [A](index.html)>><br>The list of pedestrians belonging to this group. |


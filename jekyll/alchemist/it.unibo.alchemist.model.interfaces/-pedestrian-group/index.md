---
title: PedestrianGroup
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[PedestrianGroup](index.html)



# PedestrianGroup



[jvm]\
interface [PedestrianGroup](index.html)<[T](index.html), [P](index.html) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[P](index.html)>> : [Group](../-group/index.html)<[T](index.html), [Pedestrian](../-pedestrian/index.html)<[T](index.html), [P](index.html), [A](index.html)>> 

A [Group](../-group/index.html) of [Pedestrian](../-pedestrian/index.html)s.



## Functions


| Name | Summary |
|---|---|
| [addMember](index.html#-660227767%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [addMember](index.html#-660227767%2FFunctions%2F-134779887)(node: [Pedestrian](../-pedestrian/index.html)<[T](index.html), [P](index.html), [A](index.html)>): [Group](../-group/index.html)<[T](index.html), [Pedestrian](../-pedestrian/index.html)<[T](index.html), [P](index.html), [A](index.html)>><br>Add a node in this group if not already part of it. |
| [contains](index.html#-1711138971%2FFunctions%2F-134779887) | [jvm]<br>open fun [contains](index.html#-1711138971%2FFunctions%2F-134779887)(node: [Pedestrian](../-pedestrian/index.html)<[T](index.html), [P](index.html), [A](index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Whether a node belongs to this group or not. |
| [removeMember](index.html#623604262%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [removeMember](index.html#623604262%2FFunctions%2F-134779887)(node: [Pedestrian](../-pedestrian/index.html)<[T](index.html), [P](index.html), [A](index.html)>): [Group](../-group/index.html)<[T](index.html), [Pedestrian](../-pedestrian/index.html)<[T](index.html), [P](index.html), [A](index.html)>><br>Remove a node from this group. |


## Properties


| Name | Summary |
|---|---|
| [members](index.html#-20452785%2FProperties%2F-134779887) | [jvm]<br>abstract val [members](index.html#-20452785%2FProperties%2F-134779887): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Pedestrian](../-pedestrian/index.html)<[T](index.html), [P](index.html), [A](index.html)>><br>The list of pedestrians belonging to this group. |


## Inheritors


| Name |
|---|
| [Alone](../../it.unibo.alchemist.model.implementations.groups/-alone/index.html) |
| [PedestrianGroup2D](../-pedestrian-group2-d/index.html) |


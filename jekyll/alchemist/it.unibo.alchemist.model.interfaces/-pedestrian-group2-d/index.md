---
title: PedestrianGroup2D
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[PedestrianGroup2D](index.html)



# PedestrianGroup2D



[jvm]\
interface [PedestrianGroup2D](index.html)<[T](index.html)> : [PedestrianGroup](../-pedestrian-group/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html)> 

A [PedestrianGroup](../-pedestrian-group/index.html) featuring bidimensional pedestrians.



## Functions


| Name | Summary |
|---|---|
| [addMember](index.html#-1652640863%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [addMember](index.html#-1652640863%2FFunctions%2F-134779887)(node: [Pedestrian](../-pedestrian/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html)>): [Group](../-group/index.html)<[T](index.html), [Pedestrian](../-pedestrian/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html)>><br>Add a node in this group if not already part of it. |
| [contains](index.html#-575658747%2FFunctions%2F-134779887) | [jvm]<br>open fun [contains](index.html#-575658747%2FFunctions%2F-134779887)(node: [Pedestrian](../-pedestrian/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Whether a node belongs to this group or not. |
| [removeMember](index.html#-1729755292%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [removeMember](index.html#-1729755292%2FFunctions%2F-134779887)(node: [Pedestrian](../-pedestrian/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html)>): [Group](../-group/index.html)<[T](index.html), [Pedestrian](../-pedestrian/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html)>><br>Remove a node from this group. |


## Properties


| Name | Summary |
|---|---|
| [members](index.html#1093635901%2FProperties%2F-134779887) | [jvm]<br>abstract val [members](index.html#1093635901%2FProperties%2F-134779887): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Pedestrian](../-pedestrian/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html)>><br>The list of pedestrians belonging to this group. |


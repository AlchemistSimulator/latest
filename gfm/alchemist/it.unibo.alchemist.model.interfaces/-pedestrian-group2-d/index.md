//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[PedestrianGroup2D](index.md)

# PedestrianGroup2D

[jvm]\
interface [PedestrianGroup2D](index.md)<[T](index.md)> : [PedestrianGroup](../-pedestrian-group/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.md)> 

A [PedestrianGroup](../-pedestrian-group/index.md) featuring bidimensional pedestrians.

## Functions

| Name | Summary |
|---|---|
| [addMember](index.md#-1652640863%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [addMember](index.md#-1652640863%2FFunctions%2F-267951372)(node: [Pedestrian](../-pedestrian/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.md)>): [Group](../-group/index.md)<[T](index.md), [Pedestrian](../-pedestrian/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.md)>><br>Add a node in this group if not already part of it. |
| [contains](index.md#-575658747%2FFunctions%2F-267951372) | [jvm]<br>open fun [contains](index.md#-575658747%2FFunctions%2F-267951372)(node: [Pedestrian](../-pedestrian/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Whether a node belongs to this group or not. |
| [removeMember](index.md#-1729755292%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [removeMember](index.md#-1729755292%2FFunctions%2F-267951372)(node: [Pedestrian](../-pedestrian/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.md)>): [Group](../-group/index.md)<[T](index.md), [Pedestrian](../-pedestrian/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.md)>><br>Remove a node from this group. |

## Properties

| Name | Summary |
|---|---|
| [members](index.md#1093635901%2FProperties%2F-267951372) | [jvm]<br>abstract val [members](index.md#1093635901%2FProperties%2F-267951372): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Pedestrian](../-pedestrian/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.md)>><br>The list of pedestrians belonging to this group. |

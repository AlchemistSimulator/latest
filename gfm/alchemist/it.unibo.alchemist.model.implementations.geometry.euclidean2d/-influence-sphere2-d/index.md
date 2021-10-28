//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.geometry.euclidean2d](../index.md)/[InfluenceSphere2D](index.md)

# InfluenceSphere2D

[jvm]\
open class [InfluenceSphere2D](index.md)<[T](index.md)>(**env**: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md)<[T](index.md)>, **owner**: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, **shape**: [Euclidean2DShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.md#1496739300%2FClasslikes%2F-267951372)) : [InfluenceSphere](../../it.unibo.alchemist.model.interfaces.geometry/-influence-sphere/index.md)

A sphere of influence in the Euclidean world.

## Parameters

jvm

| | |
|---|---|
| env | the environment where this sphere of influence is. |
| owner | the node who owns this sphere of influence. |
| shape | the shape of this sphere of influence |

## Constructors

| | |
|---|---|
| [InfluenceSphere2D](-influence-sphere2-d.md) | [jvm]<br>fun <[T](index.md)> [InfluenceSphere2D](-influence-sphere2-d.md)(env: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md)<[T](index.md)>, owner: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, shape: [Euclidean2DShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.md#1496739300%2FClasslikes%2F-267951372))<br>    the environment where this sphere of influence is. |

## Functions

| Name | Summary |
|---|---|
| [influentialNodes](influential-nodes.md) | [jvm]<br>open override fun [influentialNodes](influential-nodes.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>><br>The list of nodes relevant for this sphere of influence. |

## Inheritors

| Name |
|---|
| [FieldOfView2D](../-field-of-view2-d/index.md) |

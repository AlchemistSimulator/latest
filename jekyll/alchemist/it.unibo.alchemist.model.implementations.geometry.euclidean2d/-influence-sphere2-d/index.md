---
title: InfluenceSphere2D
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.geometry.euclidean2d](../index.html)/[InfluenceSphere2D](index.html)



# InfluenceSphere2D



[jvm]\
open class [InfluenceSphere2D](index.html)<[T](index.html)>(**env**: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.html)<[T](index.html)>, **owner**: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, **shape**: [Euclidean2DShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.html#1496739300%2FClasslikes%2F-134779887)) : [InfluenceSphere](../../it.unibo.alchemist.model.interfaces.geometry/-influence-sphere/index.html)

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
| [InfluenceSphere2D](-influence-sphere2-d.html) | [jvm]<br>fun <[T](index.html)> [InfluenceSphere2D](-influence-sphere2-d.html)(env: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.html)<[T](index.html)>, owner: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, shape: [Euclidean2DShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.html#1496739300%2FClasslikes%2F-134779887))<br>    the environment where this sphere of influence is. |


## Functions


| Name | Summary |
|---|---|
| [influentialNodes](influential-nodes.html) | [jvm]<br>open override fun [influentialNodes](influential-nodes.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>><br>The list of nodes relevant for this sphere of influence. |


## Inheritors


| Name |
|---|
| [FieldOfView2D](../-field-of-view2-d/index.html) |


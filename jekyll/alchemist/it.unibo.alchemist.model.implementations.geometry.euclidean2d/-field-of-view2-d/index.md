---
title: FieldOfView2D
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.geometry.euclidean2d](../index.html)/[FieldOfView2D](index.html)



# FieldOfView2D



[jvm]\
class [FieldOfView2D](index.html)<[T](index.html)>(**env**: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.html)<[T](index.html)>, **owner**: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, **distance**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **aperture**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [InfluenceSphere2D](../-influence-sphere2-d/index.html)<[T](index.html)> 

A sphere of influence representing the sight of a node in the Euclidean world.



## Parameters


jvm

| | |
|---|---|
| env | the environment where this sphere of influence is. |
| owner | the node who owns this sphere of influence. |
| distance | the distance in meters at which the sight arrives. |
| aperture | the amplitude of the field of view in radians. |



## Constructors


| | |
|---|---|
| [FieldOfView2D](-field-of-view2-d.html) | [jvm]<br>fun <[T](index.html)> [FieldOfView2D](-field-of-view2-d.html)(env: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.html)<[T](index.html)>, owner: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, distance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), aperture: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>    the environment where this sphere of influence is. |


## Functions


| Name | Summary |
|---|---|
| [influentialNodes](../-influence-sphere2-d/influential-nodes.html) | [jvm]<br>open override fun [influentialNodes](../-influence-sphere2-d/influential-nodes.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>><br>The list of nodes relevant for this sphere of influence. |


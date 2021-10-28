//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.geometry.euclidean2d](../index.md)/[FieldOfView2D](index.md)

# FieldOfView2D

[jvm]\
class [FieldOfView2D](index.md)<[T](index.md)>(**env**: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md)<[T](index.md)>, **owner**: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, **distance**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **aperture**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [InfluenceSphere2D](../-influence-sphere2-d/index.md)<[T](index.md)> 

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
| [FieldOfView2D](-field-of-view2-d.md) | [jvm]<br>fun <[T](index.md)> [FieldOfView2D](-field-of-view2-d.md)(env: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md)<[T](index.md)>, owner: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, distance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), aperture: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>    the environment where this sphere of influence is. |

## Functions

| Name | Summary |
|---|---|
| [influentialNodes](../-influence-sphere2-d/influential-nodes.md) | [jvm]<br>open override fun [influentialNodes](../-influence-sphere2-d/influential-nodes.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>><br>The list of nodes relevant for this sphere of influence. |

//[alchemist](../../../../index.md)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d](../../index.md)/[Intersection2D](../index.md)/[SinglePoint](index.md)

# SinglePoint

[jvm]\
data class [SinglePoint](index.md)<[P](index.md) : [Vector2D](../../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.md)<[P](index.md)>>(**point**: [P](index.md)) : [Intersection2D](../index.md)<[P](index.md)> 

Objects intersect in a single [point](point.md).

## Constructors

| | |
|---|---|
| [SinglePoint](-single-point.md) | [jvm]<br>fun <[P](index.md) : [Vector2D](../../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.md)<[P](index.md)>> [SinglePoint](-single-point.md)(point: [P](index.md)) |

## Properties

| Name | Summary |
|---|---|
| [asList](as-list.md) | [jvm]<br>open override val [asList](as-list.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[P](index.md)><br>List of intersection points (in case of infinite points this is empty). |
| [point](point.md) | [jvm]<br>val [point](point.md): [P](index.md) |

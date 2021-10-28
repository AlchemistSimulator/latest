//[alchemist](../../../../index.md)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d](../../index.md)/[Intersection2D](../index.md)/[MultiplePoints](index.md)

# MultiplePoints

[jvm]\
data class [MultiplePoints](index.md)<[P](index.md) : [Vector2D](../../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.md)<[P](index.md)>>(**points**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[P](index.md)>) : [Intersection2D](../index.md)<[P](index.md)> 

Objects intersect in a discrete number of [points](points.md).

## Constructors

| | |
|---|---|
| [MultiplePoints](-multiple-points.md) | [jvm]<br>fun <[P](index.md) : [Vector2D](../../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.md)<[P](index.md)>> [MultiplePoints](-multiple-points.md)(points: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[P](index.md)>) |

## Properties

| Name | Summary |
|---|---|
| [asList](as-list.md) | [jvm]<br>open override val [asList](as-list.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[P](index.md)><br>List of intersection points (in case of infinite points this is empty). |
| [points](points.md) | [jvm]<br>val [points](points.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[P](index.md)> |

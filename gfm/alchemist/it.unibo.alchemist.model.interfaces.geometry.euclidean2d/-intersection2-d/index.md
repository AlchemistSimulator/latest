//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d](../index.md)/[Intersection2D](index.md)

# Intersection2D

[jvm]\
sealed class [Intersection2D](index.md)<out [V](index.md)>

Describes the result an intersection operation in an euclidean 2D space. Type [V](index.md) must extend [Vector2D](../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.md). The requirement is not explicitly enforced to allow the class to work covariantly.

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [jvm]<br>object [Companion](-companion/index.md) |
| [InfinitePoints](-infinite-points/index.md) | [jvm]<br>object [InfinitePoints](-infinite-points/index.md) : [Intersection2D](index.md)<[Nothing](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)> <br>Objects intersect in infinite points (e.g. |
| [MultiplePoints](-multiple-points/index.md) | [jvm]<br>data class [MultiplePoints](-multiple-points/index.md)<[P](-multiple-points/index.md) : [Vector2D](../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.md)<[P](-multiple-points/index.md)>>(**points**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[P](-multiple-points/index.md)>) : [Intersection2D](index.md)<[P](-multiple-points/index.md)> <br>Objects intersect in a discrete number of [points](-multiple-points/points.md). |
| [None](-none/index.md) | [jvm]<br>object [None](-none/index.md) : [Intersection2D](index.md)<[Nothing](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)> <br>Objects do not intersect. |
| [SinglePoint](-single-point/index.md) | [jvm]<br>data class [SinglePoint](-single-point/index.md)<[P](-single-point/index.md) : [Vector2D](../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.md)<[P](-single-point/index.md)>>(**point**: [P](-single-point/index.md)) : [Intersection2D](index.md)<[P](-single-point/index.md)> <br>Objects intersect in a single [point](-single-point/point.md). |

## Properties

| Name | Summary |
|---|---|
| [asList](as-list.md) | [jvm]<br>open val [asList](as-list.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[V](index.md)><br>List of intersection points (in case of infinite points this is empty). |

## Inheritors

| Name |
|---|
| [Intersection2D](-none/index.md) |
| [Intersection2D](-single-point/index.md) |
| [Intersection2D](-multiple-points/index.md) |
| [Intersection2D](-infinite-points/index.md) |

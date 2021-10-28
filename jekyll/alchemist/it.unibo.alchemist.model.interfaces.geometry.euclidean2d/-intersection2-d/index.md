---
title: Intersection2D
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d](../index.html)/[Intersection2D](index.html)



# Intersection2D



[jvm]\
sealed class [Intersection2D](index.html)<out [V](index.html)>

Describes the result an intersection operation in an euclidean 2D space. Type [V](index.html) must extend [Vector2D](../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.html). The requirement is not explicitly enforced to allow the class to work covariantly.



## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |
| [InfinitePoints](-infinite-points/index.html) | [jvm]<br>object [InfinitePoints](-infinite-points/index.html) : [Intersection2D](index.html)<[Nothing](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)> <br>Objects intersect in infinite points (e.g. |
| [MultiplePoints](-multiple-points/index.html) | [jvm]<br>data class [MultiplePoints](-multiple-points/index.html)<[P](-multiple-points/index.html) : [Vector2D](../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.html)<[P](-multiple-points/index.html)>>(**points**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[P](-multiple-points/index.html)>) : [Intersection2D](index.html)<[P](-multiple-points/index.html)> <br>Objects intersect in a discrete number of [points](-multiple-points/points.html). |
| [None](-none/index.html) | [jvm]<br>object [None](-none/index.html) : [Intersection2D](index.html)<[Nothing](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)> <br>Objects do not intersect. |
| [SinglePoint](-single-point/index.html) | [jvm]<br>data class [SinglePoint](-single-point/index.html)<[P](-single-point/index.html) : [Vector2D](../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.html)<[P](-single-point/index.html)>>(**point**: [P](-single-point/index.html)) : [Intersection2D](index.html)<[P](-single-point/index.html)> <br>Objects intersect in a single [point](-single-point/point.html). |


## Properties


| Name | Summary |
|---|---|
| [asList](as-list.html) | [jvm]<br>open val [asList](as-list.html): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[V](index.html)><br>List of intersection points (in case of infinite points this is empty). |


## Inheritors


| Name |
|---|
| [Intersection2D](-none/index.html) |
| [Intersection2D](-single-point/index.html) |
| [Intersection2D](-multiple-points/index.html) |
| [Intersection2D](-infinite-points/index.html) |


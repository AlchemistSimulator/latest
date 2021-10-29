---
title: MultiplePoints
---
//[alchemist](../../../../index.html)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d](../../index.html)/[Intersection2D](../index.html)/[MultiplePoints](index.html)



# MultiplePoints



[jvm]\
data class [MultiplePoints](index.html)<[P](index.html) : [Vector2D](../../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.html)<[P](index.html)>>(**points**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[P](index.html)>) : [Intersection2D](../index.html)<[P](index.html)> 

Objects intersect in a discrete number of [points](points.html).



## Constructors


| | |
|---|---|
| [MultiplePoints](-multiple-points.html) | [jvm]<br>fun <[P](index.html) : [Vector2D](../../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.html)<[P](index.html)>> [MultiplePoints](-multiple-points.html)(points: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[P](index.html)>) |


## Properties


| Name | Summary |
|---|---|
| [asList](as-list.html) | [jvm]<br>open override val [asList](as-list.html): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[P](index.html)><br>List of intersection points (in case of infinite points this is empty). |
| [points](points.html) | [jvm]<br>val [points](points.html): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[P](index.html)> |


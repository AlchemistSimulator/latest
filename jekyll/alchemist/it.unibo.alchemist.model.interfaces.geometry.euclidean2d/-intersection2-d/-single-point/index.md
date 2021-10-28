---
title: SinglePoint
---
//[alchemist](../../../../index.html)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d](../../index.html)/[Intersection2D](../index.html)/[SinglePoint](index.html)



# SinglePoint



[jvm]\
data class [SinglePoint](index.html)<[P](index.html) : [Vector2D](../../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.html)<[P](index.html)>>(**point**: [P](index.html)) : [Intersection2D](../index.html)<[P](index.html)> 

Objects intersect in a single [point](point.html).



## Constructors


| | |
|---|---|
| [SinglePoint](-single-point.html) | [jvm]<br>fun <[P](index.html) : [Vector2D](../../../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.html)<[P](index.html)>> [SinglePoint](-single-point.html)(point: [P](index.html)) |


## Properties


| Name | Summary |
|---|---|
| [asList](as-list.html) | [jvm]<br>open override val [asList](as-list.html): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[P](index.html)><br>List of intersection points (in case of infinite points this is empty). |
| [point](point.html) | [jvm]<br>val [point](point.html): [P](index.html) |


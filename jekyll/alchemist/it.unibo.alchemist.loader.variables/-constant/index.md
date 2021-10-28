---
title: Constant
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.variables](../index.html)/[Constant](index.html)



# Constant



[jvm]\
class [Constant](index.html)<[V](index.html)>(**value**: [V](index.html)) : [DependentVariable](../-dependent-variable/index.html)<[V](index.html)> 

A constant [value](value.html), expressed as a variable to promote code reuse in Alchemist specifications.



## Constructors


| | |
|---|---|
| [Constant](-constant.html) | [jvm]<br>fun <[V](index.html)> [Constant](-constant.html)(value: [V](index.html)) |


## Functions


| Name | Summary |
|---|---|
| [getWith](get-with.html) | [jvm]<br>open override fun [getWith](get-with.html)(variables: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [V](index.html)<br>Given the current controlled variables, computes the current values for this variable. |


## Properties


| Name | Summary |
|---|---|
| [value](value.html) | [jvm]<br>val [value](value.html): [V](index.html) |


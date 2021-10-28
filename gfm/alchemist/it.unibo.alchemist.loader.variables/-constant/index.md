//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.variables](../index.md)/[Constant](index.md)

# Constant

[jvm]\
class [Constant](index.md)<[V](index.md)>(**value**: [V](index.md)) : [DependentVariable](../-dependent-variable/index.md)<[V](index.md)> 

A constant [value](value.md), expressed as a variable to promote code reuse in Alchemist specifications.

## Constructors

| | |
|---|---|
| [Constant](-constant.md) | [jvm]<br>fun <[V](index.md)> [Constant](-constant.md)(value: [V](index.md)) |

## Functions

| Name | Summary |
|---|---|
| [getWith](get-with.md) | [jvm]<br>open override fun [getWith](get-with.md)(variables: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [V](index.md)<br>Given the current controlled variables, computes the current values for this variable. |

## Properties

| Name | Summary |
|---|---|
| [value](value.md) | [jvm]<br>val [value](value.md): [V](index.md) |

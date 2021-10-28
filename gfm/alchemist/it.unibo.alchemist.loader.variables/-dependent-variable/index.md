//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.variables](../index.md)/[DependentVariable](index.md)

# DependentVariable

[jvm]\
@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()

interface [DependentVariable](index.md)<[V](index.md)> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

A dependent variable, namely a variable whose value can be obtained given the values of other variables.

## Parameters

jvm

| | |
|---|---|
| <V> | value type of the variable |

## Functions

| Name | Summary |
|---|---|
| [getWith](get-with.md) | [jvm]<br>abstract fun [getWith](get-with.md)(variables: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [V](../-printable-variable/index.md)<br>Given the current controlled variables, computes the current values for this variable. |

## Inheritors

| Name |
|---|
| [NumericConstant](../-numeric-constant/index.md) |
| [Constant](../-constant/index.md) |
| [JSR223Variable](../-j-s-r223-variable/index.md) |

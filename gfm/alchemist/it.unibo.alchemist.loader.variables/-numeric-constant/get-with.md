//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.variables](../index.md)/[NumericConstant](index.md)/[getWith](get-with.md)

# getWith

[jvm]\
open fun [getWith](get-with.md)(variables: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)

Given the current controlled variables, computes the current values for this variable.

#### Return

the value for this value

## Parameters

jvm

| | |
|---|---|
| variables | a mapping between variable names and values |

#### Throws

| | |
|---|---|
| [java.lang.IllegalStateException](https://docs.oracle.com/javase/8/docs/api/java/lang/IllegalStateException.html) | if the value can not be computed, e.g. because there are unassigned required variables |

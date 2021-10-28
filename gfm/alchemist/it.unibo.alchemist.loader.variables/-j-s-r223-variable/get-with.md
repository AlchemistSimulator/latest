//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.variables](../index.md)/[JSR223Variable](index.md)/[getWith](get-with.md)

# getWith

[jvm]\
open override fun [getWith](get-with.md)(variables: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>): [R](index.md)

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
| [kotlin.IllegalStateException](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-illegal-state-exception/index.html) | if the value can not be computed, e.g. because there are unassigned required variables |

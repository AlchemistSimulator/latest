//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Context](index.md)

# Context

[jvm]\
enum [Context](index.md)

This enum describes the possible contexts for a given [Action](../-action/index.md) or [Condition](../-condition/index.md). A context represents the elements which are read for a [Condition](../-condition/index.md) and the elements that may be subject of modifications for an [Action](../-action/index.md). Choosing the right [Context](index.md) is crucial: if it's too restricted the simulation will be invalid, if it's too wide it WILL impact dramatically on performances. Contexts are used internally to better determine dependencies among reactions. See [ this paper](http://apice.unibo.it/xwiki/bin/view/Publications/PianiniMASS11) for further information about the usage of contexts.

## Entries

| | |
|---|---|
| [GLOBAL](-g-l-o-b-a-l/index.md) | [jvm]<br>[GLOBAL](-g-l-o-b-a-l/index.md)<br>The reaction potentially influences every other reaction. |
| [LOCAL](-l-o-c-a-l/index.md) | [jvm]<br>[LOCAL](-l-o-c-a-l/index.md)<br>The reaction can influence only the node in which it's placed. |
| [NEIGHBORHOOD](-n-e-i-g-h-b-o-r-h-o-o-d/index.md) | [jvm]<br>[NEIGHBORHOOD](-n-e-i-g-h-b-o-r-h-o-o-d/index.md)<br>The reaction may influence its node and the neighboring ones. |

## Functions

| Name | Summary |
|---|---|
| [getWider](get-wider.md) | [jvm]<br>open fun [getWider](get-wider.md)(c1: [Context](index.md), c2: [Context](index.md)): [Context](index.md)<br>context to compare |
| [valueOf](value-of.md) | [jvm]<br>open fun [valueOf](value-of.md)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Context](index.md) |
| [values](values.md) | [jvm]<br>open fun [values](values.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Context](index.md)> |

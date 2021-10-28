---
title: Context
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Context](index.html)



# Context



[jvm]\
enum [Context](index.html)

This enum describes the possible contexts for a given [Action](../-action/index.html) or [Condition](../-condition/index.html). A context represents the elements which are read for a [Condition](../-condition/index.html) and the elements that may be subject of modifications for an [Action](../-action/index.html). Choosing the right [Context](index.html) is crucial: if it's too restricted the simulation will be invalid, if it's too wide it WILL impact dramatically on performances. Contexts are used internally to better determine dependencies among reactions. See [ this paper](http://apice.unibo.it/xwiki/bin/view/Publications/PianiniMASS11) for further information about the usage of contexts.



## Entries


| | |
|---|---|
| [GLOBAL](-g-l-o-b-a-l/index.html) | [jvm]<br>[GLOBAL](-g-l-o-b-a-l/index.html)<br>The reaction potentially influences every other reaction. |
| [LOCAL](-l-o-c-a-l/index.html) | [jvm]<br>[LOCAL](-l-o-c-a-l/index.html)<br>The reaction can influence only the node in which it's placed. |
| [NEIGHBORHOOD](-n-e-i-g-h-b-o-r-h-o-o-d/index.html) | [jvm]<br>[NEIGHBORHOOD](-n-e-i-g-h-b-o-r-h-o-o-d/index.html)<br>The reaction may influence its node and the neighboring ones. |


## Functions


| Name | Summary |
|---|---|
| [getWider](get-wider.html) | [jvm]<br>open fun [getWider](get-wider.html)(c1: [Context](index.html), c2: [Context](index.html)): [Context](index.html)<br>context to compare |
| [valueOf](value-of.html) | [jvm]<br>open fun [valueOf](value-of.html)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Context](index.html) |
| [values](values.html) | [jvm]<br>open fun [values](values.html)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Context](index.html)> |


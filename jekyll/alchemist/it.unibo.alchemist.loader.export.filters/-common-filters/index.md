---
title: CommonFilters
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.export.filters](../index.html)/[CommonFilters](index.html)



# CommonFilters



[jvm]\
enum [CommonFilters](index.html)

Utilities with the most common filtering operations on values.



## Entries


| | |
|---|---|
| [NOFILTER](-n-o-f-i-l-t-e-r/index.html) | [jvm]<br>[NOFILTER](-n-o-f-i-l-t-e-r/index.html)<br>Keeps all values. |
| [ONLYFINITE](-o-n-l-y-f-i-n-i-t-e/index.html) | [jvm]<br>[ONLYFINITE](-o-n-l-y-f-i-n-i-t-e/index.html)<br>Keeps only finite values ([isFinite](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html#isFinite-double-) returns true). |
| [FILTERINFINITY](-f-i-l-t-e-r-i-n-f-i-n-i-t-y/index.html) | [jvm]<br>[FILTERINFINITY](-f-i-l-t-e-r-i-n-f-i-n-i-t-y/index.html)<br>Remove all values that match [isInfinite](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html#isInfinite-double-) ([NaN](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html#NaN--) don't get filtered). |
| [FILTERNAN](-f-i-l-t-e-r-n-a-n/index.html) | [jvm]<br>[FILTERNAN](-f-i-l-t-e-r-n-a-n/index.html)<br>Remove all [NaN](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html#NaN--) values. |


## Functions


| Name | Summary |
|---|---|
| [fromString](from-string.html) | [jvm]<br>open fun [fromString](from-string.html)(input: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [FilteringPolicy](../../it.unibo.alchemist.loader.export/-filtering-policy/index.html)<br>a [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) matching a [FilteringPolicy](../../it.unibo.alchemist.loader.export/-filtering-policy/index.html) name (one of the values of [CommonFilters](index.html)) |
| [getFilteringPolicy](get-filtering-policy.html) | [jvm]<br>open fun [getFilteringPolicy](get-filtering-policy.html)(): [FilteringPolicy](../../it.unibo.alchemist.loader.export/-filtering-policy/index.html)<br>the [FilteringPolicy](../../it.unibo.alchemist.loader.export/-filtering-policy/index.html) |
| [valueOf](value-of.html) | [jvm]<br>open fun [valueOf](value-of.html)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [CommonFilters](index.html) |
| [values](values.html) | [jvm]<br>open fun [values](values.html)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[CommonFilters](index.html)> |


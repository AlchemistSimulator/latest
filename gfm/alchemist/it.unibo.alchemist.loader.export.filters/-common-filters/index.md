//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.export.filters](../index.md)/[CommonFilters](index.md)

# CommonFilters

[jvm]\
enum [CommonFilters](index.md)

Utilities with the most common filtering operations on values.

## Entries

| | |
|---|---|
| [NOFILTER](-n-o-f-i-l-t-e-r/index.md) | [jvm]<br>[NOFILTER](-n-o-f-i-l-t-e-r/index.md)<br>Keeps all values. |
| [ONLYFINITE](-o-n-l-y-f-i-n-i-t-e/index.md) | [jvm]<br>[ONLYFINITE](-o-n-l-y-f-i-n-i-t-e/index.md)<br>Keeps only finite values ([isFinite](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html#isFinite-double-) returns true). |
| [FILTERINFINITY](-f-i-l-t-e-r-i-n-f-i-n-i-t-y/index.md) | [jvm]<br>[FILTERINFINITY](-f-i-l-t-e-r-i-n-f-i-n-i-t-y/index.md)<br>Remove all values that match [isInfinite](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html#isInfinite-double-) ([NaN](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html#NaN--) don't get filtered). |
| [FILTERNAN](-f-i-l-t-e-r-n-a-n/index.md) | [jvm]<br>[FILTERNAN](-f-i-l-t-e-r-n-a-n/index.md)<br>Remove all [NaN](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html#NaN--) values. |

## Functions

| Name | Summary |
|---|---|
| [fromString](from-string.md) | [jvm]<br>open fun [fromString](from-string.md)(input: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [FilteringPolicy](../../it.unibo.alchemist.loader.export/-filtering-policy/index.md)<br>a [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) matching a [FilteringPolicy](../../it.unibo.alchemist.loader.export/-filtering-policy/index.md) name (one of the values of [CommonFilters](index.md)) |
| [getFilteringPolicy](get-filtering-policy.md) | [jvm]<br>open fun [getFilteringPolicy](get-filtering-policy.md)(): [FilteringPolicy](../../it.unibo.alchemist.loader.export/-filtering-policy/index.md)<br>the [FilteringPolicy](../../it.unibo.alchemist.loader.export/-filtering-policy/index.md) |
| [valueOf](value-of.md) | [jvm]<br>open fun [valueOf](value-of.md)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [CommonFilters](index.md) |
| [values](values.md) | [jvm]<br>open fun [values](values.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[CommonFilters](index.md)> |

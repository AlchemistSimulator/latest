//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.isolines](../index.md)/[ConrecIsolinesFinder](index.md)

# ConrecIsolinesFinder

[jvm]\
open class [ConrecIsolinesFinder](index.md) : [IsolinesFinder](../-isolines-finder/index.md)

Conrec algorithm adapter to IsolinesFinder interface.

## Constructors

| | |
|---|---|
| [ConrecIsolinesFinder](-conrec-isolines-finder.md) | [jvm]<br>open fun [ConrecIsolinesFinder](-conrec-isolines-finder.md)(factory: [IsolinesFactory](../-isolines-factory/index.md))<br>- the factory used to create segments and isolines |

## Functions

| Name | Summary |
|---|---|
| [findIsolines](find-isolines.md) | [jvm]<br>open fun [findIsolines](find-isolines.md)(function: [IsolinesFinder.BidimensionalFunction](../-isolines-finder/-bidimensional-function/index.md), diagonal: [Segment2D](../-segment2-d/index.md), levels: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)>): [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Isoline](../-isoline/index.md)><br>open fun [findIsolines](find-isolines.md)(function: [IsolinesFinder.BidimensionalFunction](../-isolines-finder/-bidimensional-function/index.md), x1: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), y1: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), x2: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), y2: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), levels: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)>): [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Isoline](../-isoline/index.md)><br>Find the isolines of the given function. |

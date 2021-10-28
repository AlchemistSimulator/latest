//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.isolines](../index.md)/[IsolinesFinder](index.md)

# IsolinesFinder

[jvm]\
interface [IsolinesFinder](index.md)

Defines an object capable of finding isolines (i.e. an isolines finding algorithm).

## Types

| Name | Summary |
|---|---|
| [BidimensionalFunction](-bidimensional-function/index.md) | [jvm]<br>@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()<br>interface [BidimensionalFunction](-bidimensional-function/index.md)<br>Defines a basic bidimensional function. |

## Functions

| Name | Summary |
|---|---|
| [findIsolines](find-isolines.md) | [jvm]<br>abstract fun [findIsolines](find-isolines.md)(function: [IsolinesFinder.BidimensionalFunction](-bidimensional-function/index.md), diagonal: [Segment2D](../-segment2-d/index.md), levels: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)>): [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Isoline](../-isoline/index.md)><br>abstract fun [findIsolines](find-isolines.md)(function: [IsolinesFinder.BidimensionalFunction](-bidimensional-function/index.md), x1: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), y1: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), x2: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), y2: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), levels: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)>): [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Isoline](../-isoline/index.md)><br>Find the isolines of the given function. |

## Inheritors

| Name |
|---|
| [ConrecIsolinesFinder](../-conrec-isolines-finder/index.md) |

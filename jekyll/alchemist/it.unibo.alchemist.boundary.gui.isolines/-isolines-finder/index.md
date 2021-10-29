---
title: IsolinesFinder
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.isolines](../index.html)/[IsolinesFinder](index.html)



# IsolinesFinder



[jvm]\
interface [IsolinesFinder](index.html)

Defines an object capable of finding isolines (i.e. an isolines finding algorithm).



## Types


| Name | Summary |
|---|---|
| [BidimensionalFunction](-bidimensional-function/index.html) | [jvm]<br>@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()<br>interface [BidimensionalFunction](-bidimensional-function/index.html)<br>Defines a basic bidimensional function. |


## Functions


| Name | Summary |
|---|---|
| [findIsolines](find-isolines.html) | [jvm]<br>abstract fun [findIsolines](find-isolines.html)(function: [IsolinesFinder.BidimensionalFunction](-bidimensional-function/index.html), diagonal: [Segment2D](../-segment2-d/index.html), levels: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)>): [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Isoline](../-isoline/index.html)><br>abstract fun [findIsolines](find-isolines.html)(function: [IsolinesFinder.BidimensionalFunction](-bidimensional-function/index.html), x1: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), y1: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), x2: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), y2: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), levels: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)>): [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Isoline](../-isoline/index.html)><br>Find the isolines of the given function. |


## Inheritors


| Name |
|---|
| [ConrecIsolinesFinder](../-conrec-isolines-finder/index.html) |


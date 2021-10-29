---
title: findIsolines
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.isolines](../index.html)/[ConrecIsolinesFinder](index.html)/[findIsolines](find-isolines.html)



# findIsolines



[jvm]\
open fun [findIsolines](find-isolines.html)(function: [IsolinesFinder.BidimensionalFunction](../-isolines-finder/-bidimensional-function/index.html), x1: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), y1: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), x2: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), y2: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), levels: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)>): [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Isoline](../-isoline/index.html)>



Find the isolines of the given function. You can specify which isolines will be extracted with the levels parameter: for each value included in the collection, the corresponding isoline will be extracted. Isolines will be calculated within a rectangular region defined by two opposite vertexes. This means that the algorithm will not consider the space outside the given region at all.





[jvm]\
open fun [findIsolines](find-isolines.html)(function: [IsolinesFinder.BidimensionalFunction](../-isolines-finder/-bidimensional-function/index.html), diagonal: [Segment2D](../-segment2-d/index.html), levels: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)>): [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Isoline](../-isoline/index.html)>



Find the isolines of the given function. This method is equivalent to IsolinesFinder#findIsolines(BidimensionalFunction, Number, Number, Number, Number, Collection), with the difference that it allows you to specify the diagonal of the rectangular region, instead of the four vertexes separately.





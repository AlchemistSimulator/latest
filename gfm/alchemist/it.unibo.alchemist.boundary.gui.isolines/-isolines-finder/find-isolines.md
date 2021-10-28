//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.isolines](../index.md)/[IsolinesFinder](index.md)/[findIsolines](find-isolines.md)

# findIsolines

[jvm]\
abstract fun [findIsolines](find-isolines.md)(function: [IsolinesFinder.BidimensionalFunction](-bidimensional-function/index.md), x1: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), y1: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), x2: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), y2: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), levels: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)>): [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Isoline](../-isoline/index.md)>

Find the isolines of the given function. You can specify which isolines will be extracted with the levels parameter: for each value included in the collection, the corresponding isoline will be extracted. Isolines will be calculated within a rectangular region defined by two opposite vertexes. This means that the algorithm will not consider the space outside the given region at all.

#### Return

the isolines

## Parameters

jvm

| | |
|---|---|
| function | - the function for which to calculate the isolines |
| x1 | - x coordinate of vertex 1, defining the rectangular space within which isolines will be calculated |
| y1 | - y coordinate of vertex 1, defining the rectangular space within which isolines will be calculated |
| x2 | - x coordinate of vertex 2, defining the rectangular space within which isolines will be calculated |
| y2 | - y coordinate of vertex 2, defining the rectangular space within which isolines will be calculated |
| levels | - collection containing the levels of the isolines that will be calculated |

[jvm]\
abstract fun [findIsolines](find-isolines.md)(function: [IsolinesFinder.BidimensionalFunction](-bidimensional-function/index.md), diagonal: [Segment2D](../-segment2-d/index.md), levels: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)>): [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Isoline](../-isoline/index.md)>

Find the isolines of the given function. This method is equivalent to [findIsolines](find-isolines.md), with the difference that it allows you to specify the diagonal of the rectangular region, instead of the four vertexes separately.

#### Return

the isolines

## Parameters

jvm

| | |
|---|---|
| function | - the function for which to calculate the isolines |
| diagonal | - the diagonal of the rectangular space within which isolines will be calculated |
| levels | - collection containing the levels of the isolines that will be calculated |

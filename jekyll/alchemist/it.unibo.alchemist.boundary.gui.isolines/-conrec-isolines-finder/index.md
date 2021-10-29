---
title: ConrecIsolinesFinder
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.isolines](../index.html)/[ConrecIsolinesFinder](index.html)



# ConrecIsolinesFinder



[jvm]\
open class [ConrecIsolinesFinder](index.html) : [IsolinesFinder](../-isolines-finder/index.html)

Conrec algorithm adapter to IsolinesFinder interface.



## Constructors


| | |
|---|---|
| [ConrecIsolinesFinder](-conrec-isolines-finder.html) | [jvm]<br>open fun [ConrecIsolinesFinder](-conrec-isolines-finder.html)(factory: [IsolinesFactory](../-isolines-factory/index.html))<br>- the factory used to create segments and isolines |


## Functions


| Name | Summary |
|---|---|
| [findIsolines](find-isolines.html) | [jvm]<br>open fun [findIsolines](find-isolines.html)(function: [IsolinesFinder.BidimensionalFunction](../-isolines-finder/-bidimensional-function/index.html), diagonal: [Segment2D](../-segment2-d/index.html), levels: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)>): [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Isoline](../-isoline/index.html)><br>open fun [findIsolines](find-isolines.html)(function: [IsolinesFinder.BidimensionalFunction](../-isolines-finder/-bidimensional-function/index.html), x1: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), y1: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), x2: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), y2: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), levels: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)>): [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Isoline](../-isoline/index.html)><br>Find the isolines of the given function. |


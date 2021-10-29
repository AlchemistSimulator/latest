---
title: IsolinesFactory
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.isolines](../index.html)/[IsolinesFactory](index.html)



# IsolinesFactory



[jvm]\
interface [IsolinesFactory](index.html)

A factory for the creation of the basic astractions contained in this package.



## Types


| Name | Summary |
|---|---|
| [IsolineFinders](-isoline-finders/index.html) | [jvm]<br>enum [IsolineFinders](-isoline-finders/index.html)<br>Enum containing all the available isolines finding algorithms. |


## Functions


| Name | Summary |
|---|---|
| [makeIsoline](make-isoline.html) | [jvm]<br>abstract fun [makeIsoline](make-isoline.html)(value: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), segments: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Segment2D](../-segment2-d/index.html)>): [Isoline](../-isoline/index.html)<br>Create an Isoline. |
| [makeIsolinesFinder](make-isolines-finder.html) | [jvm]<br>abstract fun [makeIsolinesFinder](make-isolines-finder.html)(algorithm: [IsolinesFactory.IsolineFinders](-isoline-finders/index.html)): [IsolinesFinder](../-isolines-finder/index.html)<br>Create an IsolinesFinder object, capable of finding isolines. |
| [makeSegment](make-segment.html) | [jvm]<br>abstract fun [makeSegment](make-segment.html)(x1: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), y1: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), x2: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), y2: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)): [Segment2D](../-segment2-d/index.html)<br>Create a 2D segment. |


## Inheritors


| Name |
|---|
| [ConcreteIsolinesFactory](../-concrete-isolines-factory/index.html) |


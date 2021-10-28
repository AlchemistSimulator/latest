//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.isolines](../index.md)/[IsolinesFactory](index.md)

# IsolinesFactory

[jvm]\
interface [IsolinesFactory](index.md)

A factory for the creation of the basic astractions contained in this package.

## Types

| Name | Summary |
|---|---|
| [IsolineFinders](-isoline-finders/index.md) | [jvm]<br>enum [IsolineFinders](-isoline-finders/index.md)<br>Enum containing all the available isolines finding algorithms. |

## Functions

| Name | Summary |
|---|---|
| [makeIsoline](make-isoline.md) | [jvm]<br>abstract fun [makeIsoline](make-isoline.md)(value: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), segments: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Segment2D](../-segment2-d/index.md)>): [Isoline](../-isoline/index.md)<br>Create an Isoline. |
| [makeIsolinesFinder](make-isolines-finder.md) | [jvm]<br>abstract fun [makeIsolinesFinder](make-isolines-finder.md)(algorithm: [IsolinesFactory.IsolineFinders](-isoline-finders/index.md)): [IsolinesFinder](../-isolines-finder/index.md)<br>Create an IsolinesFinder object, capable of finding isolines. |
| [makeSegment](make-segment.md) | [jvm]<br>abstract fun [makeSegment](make-segment.md)(x1: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), y1: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), x2: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), y2: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)): [Segment2D](../-segment2-d/index.md)<br>Create a 2D segment. |

## Inheritors

| Name |
|---|
| [ConcreteIsolinesFactory](../-concrete-isolines-factory/index.md) |

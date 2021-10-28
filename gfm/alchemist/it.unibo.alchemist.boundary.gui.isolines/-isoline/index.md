//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.isolines](../index.md)/[Isoline](index.md)

# Isoline

[jvm]\
interface [Isoline](index.md)

An isoline (also contour line, isopleth, or isarithm) of a function of two variables is a curve along which the function has a constant value, so that the curve joins points of equal value. Here the curve is approximated as a collection of 2D segments.

## Functions

| Name | Summary |
|---|---|
| [getSegments](get-segments.md) | [jvm]<br>abstract fun [getSegments](get-segments.md)(): [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Segment2D](../-segment2-d/index.md)><br>the segments forming this isoline |
| [getValue](get-value.md) | [jvm]<br>abstract fun [getValue](get-value.md)(): [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)<br>the value associated with this isoline |

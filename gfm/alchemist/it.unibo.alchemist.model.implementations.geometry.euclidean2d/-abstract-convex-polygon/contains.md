//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.geometry.euclidean2d](../index.md)/[AbstractConvexPolygon](index.md)/[contains](contains.md)

# contains

[jvm]\
open override fun [contains](contains.md)(shape: [Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Checks if the polygon contains a polygonal [java.awt.Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html) (i.e. without curved segments). A polygonal shape is contained in a polygon if all of its points are contained in (or lie on the boundary of) the latter.

## Parameters

jvm

| | |
|---|---|
| shape | the polygonal shape |

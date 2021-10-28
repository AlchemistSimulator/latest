//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d](../index.md)/[ConvexPolygon](index.md)/[intersects](intersects.md)

# intersects

[jvm]\
abstract fun [intersects](intersects.md)(shape: [Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Checks if a [java.awt.Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html) intersects the polygon, adjacent shapes are not considered to be intersecting.

## Parameters

jvm

| | |
|---|---|
| shape | the shape |

[jvm]\
abstract fun [intersects](intersects.md)(segment: [Segment2D](../-segment2-d/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Checks if a segment intersects with the polygon, segments lying on the polygon's boundary are not considered to be intersecting.

## Parameters

jvm

| | |
|---|---|
| segment | the segment |

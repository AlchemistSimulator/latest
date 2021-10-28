//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.geometry.euclidean2d](../index.md)/[AwtMutableConvexPolygon](index.md)/[intersects](intersects.md)

# intersects

[jvm]\
open override fun [intersects](intersects.md)(shape: [Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Delegated to [java.awt.geom.Area](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Area.html), this is accurate and does not consider adjacent shapes to be intersecting.

[jvm]\
open override fun [intersects](intersects.md)(other: [Euclidean2DShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.md#1496739300%2FClasslikes%2F-267951372)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Delegated to AwtEuclidean2DShape unless [other](intersects.md) is [AwtShapeCompatible](../../it.unibo.alchemist.model.implementations.geometry/-awt-shape-compatible/index.md), in which case [intersects](intersects.md) is used so as to guarantee maximum accuracy.

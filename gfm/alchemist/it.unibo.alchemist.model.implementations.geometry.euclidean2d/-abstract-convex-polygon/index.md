//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.geometry.euclidean2d](../index.md)/[AbstractConvexPolygon](index.md)

# AbstractConvexPolygon

[jvm]\
abstract class [AbstractConvexPolygon](index.md) : [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md)

An abstract [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md) providing a convexity test.

## Constructors

| | |
|---|---|
| [AbstractConvexPolygon](-abstract-convex-polygon.md) | [jvm]<br>fun [AbstractConvexPolygon](-abstract-convex-polygon.md)() |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [jvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [asAwtShape](../../it.unibo.alchemist.model.implementations.geometry/-awt-shape-compatible/as-awt-shape.md) | [jvm]<br>abstract fun [asAwtShape](../../it.unibo.alchemist.model.implementations.geometry/-awt-shape-compatible/as-awt-shape.md)(): [Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html) |
| [closestEdgeTo](closest-edge-to.md) | [jvm]<br>open override fun [closestEdgeTo](closest-edge-to.md)(segment: [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>): [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)><br>Finds the edge of the polygon closest to the provided [segment](closest-edge-to.md), i.e. |
| [contains](contains.md) | [jvm]<br>open override fun [contains](contains.md)(shape: [Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the polygon contains a polygonal [java.awt.Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html) (i.e.<br>[jvm]<br>abstract override fun [contains](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/contains.md)(vector: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the polygon contains a vector (= a point). |
| [containsBoundaryExcluded](contains-boundary-excluded.md) | [jvm]<br>open override fun [containsBoundaryExcluded](contains-boundary-excluded.md)(vector: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if a vector (= a point) is contained in the polygon, boundary excluded. |
| [containsBoundaryIncluded](contains-boundary-included.md) | [jvm]<br>open override fun [containsBoundaryIncluded](contains-boundary-included.md)(vector: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if a vector (= a point) is contained in the polygon or lies on its boundary. |
| [edges](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/edges.md) | [jvm]<br>abstract fun [edges](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/edges.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>> |
| [getEdge](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/get-edge.md) | [jvm]<br>abstract fun [getEdge](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/get-edge.md)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)><br>Depending on the implementation, this may be faster than [edges](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/edges.md). |
| [intersects](intersects.md) | [jvm]<br>open override fun [intersects](intersects.md)(segment: [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if a segment intersects with the polygon, segments lying on the polygon's boundary are not considered to be intersecting.<br>[jvm]<br>abstract fun [intersects](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/intersects.md)(shape: [Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if a [java.awt.Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html) intersects the polygon, adjacent shapes are not considered to be intersecting.<br>[jvm]<br>abstract fun [intersects](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.navigator/-extendable-convex-polygon/index.md#1376856404%2FFunctions%2F-267951372)(other: [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isAdjacentTo](is-adjacent-to.md) | [jvm]<br>open override fun [isAdjacentTo](is-adjacent-to.md)(other: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>A polygon is adjacent to another if any of its points lies on the boundary of the other. |
| [liesOnBoundary](lies-on-boundary.md) | [jvm]<br>open override fun [liesOnBoundary](lies-on-boundary.md)(vector: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if a vector (= a point) lies on the polygon's boundary. |
| [toString](to-string.md) | [jvm]<br>open override fun [toString](to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [transformed](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.navigator/-extendable-convex-polygon/index.md#-452661544%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [transformed](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.navigator/-extendable-convex-polygon/index.md#-452661544%2FFunctions%2F-267951372)(transformation: [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.md).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.md)> |
| [vertices](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/vertices.md) | [jvm]<br>abstract fun [vertices](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/vertices.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)> |

## Properties

| Name | Summary |
|---|---|
| [centroid](index.md#-1715541658%2FProperties%2F-267951372) | [jvm]<br>abstract val [centroid](index.md#-1715541658%2FProperties%2F-267951372): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md) |
| [diameter](index.md#-210658503%2FProperties%2F-267951372) | [jvm]<br>abstract val [diameter](index.md#-210658503%2FProperties%2F-267951372): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [radius](index.md#-1296422636%2FProperties%2F-267951372) | [jvm]<br>open val [radius](index.md#-1296422636%2FProperties%2F-267951372): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |

## Inheritors

| Name |
|---|
| [AwtMutableConvexPolygon](../-awt-mutable-convex-polygon/index.md) |

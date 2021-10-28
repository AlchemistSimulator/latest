---
title: ConvexPolygon
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d](../index.html)/[ConvexPolygon](index.html)



# ConvexPolygon



[jvm]\
interface [ConvexPolygon](index.html) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../-euclidean2-d-transformation/index.html)> , [AwtShapeCompatible](../../it.unibo.alchemist.model.implementations.geometry/-awt-shape-compatible/index.html)

A simple polygon (i.e. not self-intersecting and without holes) in which no line segment between two points on the boundary ever goes outside the polygon.



## Functions


| Name | Summary |
|---|---|
| [asAwtShape](../../it.unibo.alchemist.model.implementations.geometry/-awt-shape-compatible/as-awt-shape.html) | [jvm]<br>abstract fun [asAwtShape](../../it.unibo.alchemist.model.implementations.geometry/-awt-shape-compatible/as-awt-shape.html)(): [Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html) |
| [closestEdgeTo](closest-edge-to.html) | [jvm]<br>abstract fun [closestEdgeTo](closest-edge-to.html)(segment: [Segment2D](../-segment2-d/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>): [Segment2D](../-segment2-d/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)><br>Finds the edge of the polygon closest to the provided [segment](closest-edge-to.html), i.e. |
| [contains](contains.html) | [jvm]<br>abstract override fun [contains](contains.html)(vector: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the polygon contains a vector (= a point).<br>[jvm]<br>abstract fun [contains](contains.html)(shape: [Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the polygon contains a polygonal [java.awt.Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html) (i.e. |
| [containsBoundaryExcluded](contains-boundary-excluded.html) | [jvm]<br>abstract fun [containsBoundaryExcluded](contains-boundary-excluded.html)(vector: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if a vector (= a point) is contained in the polygon, boundary excluded. |
| [containsBoundaryIncluded](contains-boundary-included.html) | [jvm]<br>abstract fun [containsBoundaryIncluded](contains-boundary-included.html)(vector: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if a vector (= a point) is contained in the polygon or lies on its boundary. |
| [edges](edges.html) | [jvm]<br>abstract fun [edges](edges.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Segment2D](../-segment2-d/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>> |
| [getEdge](get-edge.html) | [jvm]<br>abstract fun [getEdge](get-edge.html)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Segment2D](../-segment2-d/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)><br>Depending on the implementation, this may be faster than [edges](edges.html). |
| [intersects](intersects.html) | [jvm]<br>abstract fun [intersects](intersects.html)(segment: [Segment2D](../-segment2-d/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if a segment intersects with the polygon, segments lying on the polygon's boundary are not considered to be intersecting.<br>[jvm]<br>abstract fun [intersects](intersects.html)(shape: [Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if a [java.awt.Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html) intersects the polygon, adjacent shapes are not considered to be intersecting.<br>[jvm]<br>abstract fun [intersects](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.navigator/-extendable-convex-polygon/index.html#1376856404%2FFunctions%2F-134779887)(other: [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../-euclidean2-d-transformation/index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isAdjacentTo](is-adjacent-to.html) | [jvm]<br>abstract fun [isAdjacentTo](is-adjacent-to.html)(other: [ConvexPolygon](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>A polygon is adjacent to another if any of its points lies on the boundary of the other. |
| [liesOnBoundary](lies-on-boundary.html) | [jvm]<br>abstract fun [liesOnBoundary](lies-on-boundary.html)(vector: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if a vector (= a point) lies on the polygon's boundary. |
| [transformed](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.navigator/-extendable-convex-polygon/index.html#-452661544%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [transformed](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.navigator/-extendable-convex-polygon/index.html#-452661544%2FFunctions%2F-134779887)(transformation: [Euclidean2DTransformation](../-euclidean2-d-transformation/index.html).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../-euclidean2-d-transformation/index.html)> |
| [vertices](vertices.html) | [jvm]<br>abstract fun [vertices](vertices.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)> |


## Properties


| Name | Summary |
|---|---|
| [centroid](index.html#25438885%2FProperties%2F-134779887) | [jvm]<br>abstract val [centroid](index.html#25438885%2FProperties%2F-134779887): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html) |
| [diameter](index.html#1530322040%2FProperties%2F-134779887) | [jvm]<br>abstract val [diameter](index.html#1530322040%2FProperties%2F-134779887): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [radius](index.html#1695329811%2FProperties%2F-134779887) | [jvm]<br>open val [radius](index.html#1695329811%2FProperties%2F-134779887): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |


## Inheritors


| Name |
|---|
| [AbstractConvexPolygon](../../it.unibo.alchemist.model.implementations.geometry.euclidean2d/-abstract-convex-polygon/index.html) |
| [MutableConvexPolygon](../-mutable-convex-polygon/index.html) |


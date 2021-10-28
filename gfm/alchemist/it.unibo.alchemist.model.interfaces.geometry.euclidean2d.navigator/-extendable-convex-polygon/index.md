//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d.navigator](../index.md)/[ExtendableConvexPolygon](index.md)

# ExtendableConvexPolygon

[jvm]\
interface [ExtendableConvexPolygon](index.md) : [MutableConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-mutable-convex-polygon/index.md)

A sophisticated [MutableConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-mutable-convex-polygon/index.md).

## Functions

| Name | Summary |
|---|---|
| [addVertex](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-mutable-convex-polygon/add-vertex.md) | [jvm]<br>abstract fun [addVertex](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-mutable-convex-polygon/add-vertex.md)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Adds a vertex to the polygon. |
| [advanceEdge](advance-edge.md) | [jvm]<br>abstract fun [advanceEdge](advance-edge.md)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), step: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Advances an edge in its normal direction. |
| [asAwtShape](../../it.unibo.alchemist.model.implementations.geometry/-awt-shape-compatible/as-awt-shape.md) | [jvm]<br>abstract fun [asAwtShape](../../it.unibo.alchemist.model.implementations.geometry/-awt-shape-compatible/as-awt-shape.md)(): [Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html) |
| [closestEdgeTo](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/closest-edge-to.md) | [jvm]<br>abstract fun [closestEdgeTo](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/closest-edge-to.md)(segment: [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>): [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)><br>Finds the edge of the polygon closest to the provided [segment](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/closest-edge-to.md), i.e. |
| [contains](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/contains.md) | [jvm]<br>abstract override fun [contains](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/contains.md)(vector: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the polygon contains a vector (= a point).<br>[jvm]<br>abstract fun [contains](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/contains.md)(shape: [Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the polygon contains a polygonal [java.awt.Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html) (i.e. |
| [containsBoundaryExcluded](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/contains-boundary-excluded.md) | [jvm]<br>abstract fun [containsBoundaryExcluded](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/contains-boundary-excluded.md)(vector: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if a vector (= a point) is contained in the polygon, boundary excluded. |
| [containsBoundaryIncluded](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/contains-boundary-included.md) | [jvm]<br>abstract fun [containsBoundaryIncluded](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/contains-boundary-included.md)(vector: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if a vector (= a point) is contained in the polygon or lies on its boundary. |
| [edges](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/edges.md) | [jvm]<br>abstract fun [edges](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/edges.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>> |
| [extend](extend.md) | [jvm]<br>abstract fun [extend](extend.md)(step: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Extends the polygon in each direction: each edge is given a chance to advance. |
| [getEdge](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/get-edge.md) | [jvm]<br>abstract fun [getEdge](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/get-edge.md)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)><br>Depending on the implementation, this may be faster than [edges](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/edges.md). |
| [intersects](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/intersects.md) | [jvm]<br>abstract fun [intersects](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/intersects.md)(segment: [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if a segment intersects with the polygon, segments lying on the polygon's boundary are not considered to be intersecting.<br>[jvm]<br>abstract fun [intersects](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/intersects.md)(shape: [Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if a [java.awt.Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html) intersects the polygon, adjacent shapes are not considered to be intersecting.<br>[jvm]<br>abstract fun [intersects](index.md#1376856404%2FFunctions%2F-267951372)(other: [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isAdjacentTo](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/is-adjacent-to.md) | [jvm]<br>abstract fun [isAdjacentTo](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/is-adjacent-to.md)(other: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>A polygon is adjacent to another if any of its points lies on the boundary of the other. |
| [liesOnBoundary](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/lies-on-boundary.md) | [jvm]<br>abstract fun [liesOnBoundary](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/lies-on-boundary.md)(vector: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if a vector (= a point) lies on the polygon's boundary. |
| [moveVertex](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-mutable-convex-polygon/move-vertex.md) | [jvm]<br>abstract fun [moveVertex](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-mutable-convex-polygon/move-vertex.md)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), newX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), newY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Moves a vertex of the polygon to a new absolute position. |
| [removeVertex](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-mutable-convex-polygon/remove-vertex.md) | [jvm]<br>abstract fun [removeVertex](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-mutable-convex-polygon/remove-vertex.md)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Removes a vertex from the polygon. |
| [replaceEdge](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-mutable-convex-polygon/replace-edge.md) | [jvm]<br>abstract fun [replaceEdge](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-mutable-convex-polygon/replace-edge.md)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), newEdge: [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Replaces an edge of the polygon. |
| [transformed](index.md#-452661544%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [transformed](index.md#-452661544%2FFunctions%2F-267951372)(transformation: [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.md).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.md)> |
| [vertices](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/vertices.md) | [jvm]<br>abstract fun [vertices](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/vertices.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)> |

## Properties

| Name | Summary |
|---|---|
| [centroid](index.md#1531700346%2FProperties%2F-267951372) | [jvm]<br>abstract val [centroid](index.md#1531700346%2FProperties%2F-267951372): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md) |
| [diameter](index.md#-1258383795%2FProperties%2F-267951372) | [jvm]<br>abstract val [diameter](index.md#-1258383795%2FProperties%2F-267951372): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [radius](index.md#-810362584%2FProperties%2F-267951372) | [jvm]<br>open val [radius](index.md#-810362584%2FProperties%2F-267951372): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |

## Inheritors

| Name |
|---|
| [ExtendableConvexPolygonInEnvironment](../../it.unibo.alchemist.model.implementations.geometry.euclidean2d.navigator/-extendable-convex-polygon-in-environment/index.md) |
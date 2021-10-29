---
title: AwtMutableConvexPolygon
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.geometry.euclidean2d](../index.html)/[AwtMutableConvexPolygon](index.html)



# AwtMutableConvexPolygon



[jvm]\
open class [AwtMutableConvexPolygon](index.html)(**vertices**: [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>) : [AbstractConvexPolygon](../-abstract-convex-polygon/index.html), [MutableConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-mutable-convex-polygon/index.html)

[MutableConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-mutable-convex-polygon/index.html) partly delegated to AwtEuclidean2DShape and java.awt.geom. Each modification operation on this object has a time complexity of O(n), where n is the number of vertices/edges. Collinear points are allowed.



## Constructors


| | |
|---|---|
| [AwtMutableConvexPolygon](-awt-mutable-convex-polygon.html) | [jvm]<br>fun [AwtMutableConvexPolygon](-awt-mutable-convex-polygon.html)(vertices: [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>) |


## Functions


| Name | Summary |
|---|---|
| [addVertex](add-vertex.html) | [jvm]<br>open override fun [addVertex](add-vertex.html)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Adds a vertex to the polygon. |
| [asAwtShape](as-awt-shape.html) | [jvm]<br>override fun [asAwtShape](as-awt-shape.html)(): [Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html) |
| [closestEdgeTo](../-abstract-convex-polygon/closest-edge-to.html) | [jvm]<br>open override fun [closestEdgeTo](../-abstract-convex-polygon/closest-edge-to.html)(segment: [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>): [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)><br>Finds the edge of the polygon closest to the provided [segment](../-abstract-convex-polygon/closest-edge-to.html), i.e. |
| [contains](../-abstract-convex-polygon/contains.html) | [jvm]<br>open override fun [contains](../-abstract-convex-polygon/contains.html)(shape: [Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the polygon contains a polygonal [java.awt.Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html) (i.e.<br>[jvm]<br>open override fun [contains](contains.html)(vector: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Delegated to AwtEuclidean2DShape (adopts the definition of insideness used by [java.awt.Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html)s). |
| [containsBoundaryExcluded](../-abstract-convex-polygon/contains-boundary-excluded.html) | [jvm]<br>open override fun [containsBoundaryExcluded](../-abstract-convex-polygon/contains-boundary-excluded.html)(vector: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if a vector (= a point) is contained in the polygon, boundary excluded. |
| [containsBoundaryIncluded](../-abstract-convex-polygon/contains-boundary-included.html) | [jvm]<br>open override fun [containsBoundaryIncluded](../-abstract-convex-polygon/contains-boundary-included.html)(vector: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if a vector (= a point) is contained in the polygon or lies on its boundary. |
| [edges](edges.html) | [jvm]<br>open override fun [edges](edges.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>> |
| [equals](equals.html) | [jvm]<br>open operator override fun [equals](equals.html)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getEdge](get-edge.html) | [jvm]<br>open override fun [getEdge](get-edge.html)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Segment2DImpl](../-segment2-d-impl/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)> |
| [hashCode](hash-code.html) | [jvm]<br>open override fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [intersects](../-abstract-convex-polygon/intersects.html) | [jvm]<br>open override fun [intersects](../-abstract-convex-polygon/intersects.html)(segment: [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if a segment intersects with the polygon, segments lying on the polygon's boundary are not considered to be intersecting.<br>[jvm]<br>open override fun [intersects](intersects.html)(other: [Euclidean2DShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.html#1496739300%2FClasslikes%2F-134779887)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Delegated to AwtEuclidean2DShape unless [other](intersects.html) is [AwtShapeCompatible](../../it.unibo.alchemist.model.implementations.geometry/-awt-shape-compatible/index.html), in which case [intersects](intersects.html) is used so as to guarantee maximum accuracy.<br>[jvm]<br>open override fun [intersects](intersects.html)(shape: [Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Delegated to [java.awt.geom.Area](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Area.html), this is accurate and does not consider adjacent shapes to be intersecting. |
| [isAdjacentTo](../-abstract-convex-polygon/is-adjacent-to.html) | [jvm]<br>open override fun [isAdjacentTo](../-abstract-convex-polygon/is-adjacent-to.html)(other: [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>A polygon is adjacent to another if any of its points lies on the boundary of the other. |
| [liesOnBoundary](../-abstract-convex-polygon/lies-on-boundary.html) | [jvm]<br>open override fun [liesOnBoundary](../-abstract-convex-polygon/lies-on-boundary.html)(vector: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if a vector (= a point) lies on the polygon's boundary. |
| [moveVertex](move-vertex.html) | [jvm]<br>open override fun [moveVertex](move-vertex.html)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), newX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), newY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Moves a vertex of the polygon to a new absolute position. |
| [removeVertex](remove-vertex.html) | [jvm]<br>open override fun [removeVertex](remove-vertex.html)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Removes a vertex from the polygon. |
| [replaceEdge](replace-edge.html) | [jvm]<br>open override fun [replaceEdge](replace-edge.html)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), newEdge: [Segment2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Replaces an edge of the polygon. |
| [toString](../-abstract-convex-polygon/to-string.html) | [jvm]<br>open override fun [toString](../-abstract-convex-polygon/to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [transformed](transformed.html) | [jvm]<br>open override fun [transformed](transformed.html)(transformation: [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html)> |
| [vertices](vertices.html) | [jvm]<br>open override fun [vertices](vertices.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)> |


## Properties


| Name | Summary |
|---|---|
| [centroid](centroid.html) | [jvm]<br>open override val [centroid](centroid.html): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html) |
| [diameter](diameter.html) | [jvm]<br>open override val [diameter](diameter.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [radius](index.html#1289619182%2FProperties%2F-134779887) | [jvm]<br>open val [radius](index.html#1289619182%2FProperties%2F-134779887): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |


## Inheritors


| Name |
|---|
| [ExtendableConvexPolygonInEnvironment](../../it.unibo.alchemist.model.implementations.geometry.euclidean2d.navigator/-extendable-convex-polygon-in-environment/index.html) |


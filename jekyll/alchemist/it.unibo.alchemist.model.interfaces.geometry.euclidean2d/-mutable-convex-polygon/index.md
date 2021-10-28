---
title: MutableConvexPolygon
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d](../index.html)/[MutableConvexPolygon](index.html)



# MutableConvexPolygon



[jvm]\
interface [MutableConvexPolygon](index.html) : [ConvexPolygon](../-convex-polygon/index.html)

A mutable [ConvexPolygon](../-convex-polygon/index.html).



## Functions


| Name | Summary |
|---|---|
| [addVertex](add-vertex.html) | [jvm]<br>abstract fun [addVertex](add-vertex.html)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Adds a vertex to the polygon. |
| [asAwtShape](../../it.unibo.alchemist.model.implementations.geometry/-awt-shape-compatible/as-awt-shape.html) | [jvm]<br>abstract fun [asAwtShape](../../it.unibo.alchemist.model.implementations.geometry/-awt-shape-compatible/as-awt-shape.html)(): [Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html) |
| [closestEdgeTo](../-convex-polygon/closest-edge-to.html) | [jvm]<br>abstract fun [closestEdgeTo](../-convex-polygon/closest-edge-to.html)(segment: [Segment2D](../-segment2-d/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>): [Segment2D](../-segment2-d/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)><br>Finds the edge of the polygon closest to the provided [segment](../-convex-polygon/closest-edge-to.html), i.e. |
| [contains](../-convex-polygon/contains.html) | [jvm]<br>abstract override fun [contains](../-convex-polygon/contains.html)(vector: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the polygon contains a vector (= a point).<br>[jvm]<br>abstract fun [contains](../-convex-polygon/contains.html)(shape: [Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the polygon contains a polygonal [java.awt.Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html) (i.e. |
| [containsBoundaryExcluded](../-convex-polygon/contains-boundary-excluded.html) | [jvm]<br>abstract fun [containsBoundaryExcluded](../-convex-polygon/contains-boundary-excluded.html)(vector: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if a vector (= a point) is contained in the polygon, boundary excluded. |
| [containsBoundaryIncluded](../-convex-polygon/contains-boundary-included.html) | [jvm]<br>abstract fun [containsBoundaryIncluded](../-convex-polygon/contains-boundary-included.html)(vector: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if a vector (= a point) is contained in the polygon or lies on its boundary. |
| [edges](../-convex-polygon/edges.html) | [jvm]<br>abstract fun [edges](../-convex-polygon/edges.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Segment2D](../-segment2-d/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>> |
| [getEdge](../-convex-polygon/get-edge.html) | [jvm]<br>abstract fun [getEdge](../-convex-polygon/get-edge.html)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Segment2D](../-segment2-d/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)><br>Depending on the implementation, this may be faster than [edges](../-convex-polygon/edges.html). |
| [intersects](../-convex-polygon/intersects.html) | [jvm]<br>abstract fun [intersects](../-convex-polygon/intersects.html)(segment: [Segment2D](../-segment2-d/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if a segment intersects with the polygon, segments lying on the polygon's boundary are not considered to be intersecting.<br>[jvm]<br>abstract fun [intersects](../-convex-polygon/intersects.html)(shape: [Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if a [java.awt.Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html) intersects the polygon, adjacent shapes are not considered to be intersecting.<br>[jvm]<br>abstract fun [intersects](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.navigator/-extendable-convex-polygon/index.html#1376856404%2FFunctions%2F-134779887)(other: [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../-euclidean2-d-transformation/index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isAdjacentTo](../-convex-polygon/is-adjacent-to.html) | [jvm]<br>abstract fun [isAdjacentTo](../-convex-polygon/is-adjacent-to.html)(other: [ConvexPolygon](../-convex-polygon/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>A polygon is adjacent to another if any of its points lies on the boundary of the other. |
| [liesOnBoundary](../-convex-polygon/lies-on-boundary.html) | [jvm]<br>abstract fun [liesOnBoundary](../-convex-polygon/lies-on-boundary.html)(vector: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if a vector (= a point) lies on the polygon's boundary. |
| [moveVertex](move-vertex.html) | [jvm]<br>abstract fun [moveVertex](move-vertex.html)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), newX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), newY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Moves a vertex of the polygon to a new absolute position. |
| [removeVertex](remove-vertex.html) | [jvm]<br>abstract fun [removeVertex](remove-vertex.html)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Removes a vertex from the polygon. |
| [replaceEdge](replace-edge.html) | [jvm]<br>abstract fun [replaceEdge](replace-edge.html)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), newEdge: [Segment2D](../-segment2-d/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Replaces an edge of the polygon. |
| [transformed](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.navigator/-extendable-convex-polygon/index.html#-452661544%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [transformed](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.navigator/-extendable-convex-polygon/index.html#-452661544%2FFunctions%2F-134779887)(transformation: [Euclidean2DTransformation](../-euclidean2-d-transformation/index.html).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../-euclidean2-d-transformation/index.html)> |
| [vertices](../-convex-polygon/vertices.html) | [jvm]<br>abstract fun [vertices](../-convex-polygon/vertices.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)> |


## Properties


| Name | Summary |
|---|---|
| [centroid](index.html#-949591209%2FProperties%2F-134779887) | [jvm]<br>abstract val [centroid](index.html#-949591209%2FProperties%2F-134779887): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html) |
| [diameter](index.html#555291946%2FProperties%2F-134779887) | [jvm]<br>abstract val [diameter](index.html#555291946%2FProperties%2F-134779887): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [radius](index.html#1059679045%2FProperties%2F-134779887) | [jvm]<br>open val [radius](index.html#1059679045%2FProperties%2F-134779887): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |


## Inheritors


| Name |
|---|
| [AwtMutableConvexPolygon](../../it.unibo.alchemist.model.implementations.geometry.euclidean2d/-awt-mutable-convex-polygon/index.html) |
| [ExtendableConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.navigator/-extendable-convex-polygon/index.html) |


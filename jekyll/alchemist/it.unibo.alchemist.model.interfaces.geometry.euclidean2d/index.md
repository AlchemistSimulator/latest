---
title: it.unibo.alchemist.model.interfaces.geometry.euclidean2d
---
//[alchemist](../../index.html)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d](index.html)



# Package it.unibo.alchemist.model.interfaces.geometry.euclidean2d



## Types


| Name | Summary |
|---|---|
| [ConvexPolygon](-convex-polygon/index.html) | [jvm]<br>interface [ConvexPolygon](-convex-polygon/index.html) : [ConvexGeometricShape](../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[Euclidean2DPosition](../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](-euclidean2-d-transformation/index.html)> , [AwtShapeCompatible](../it.unibo.alchemist.model.implementations.geometry/-awt-shape-compatible/index.html)<br>A simple polygon (i.e. |
| [Euclidean2DConvexShape](index.html#-786369621%2FClasslikes%2F-134779887) | [jvm]<br>typealias [Euclidean2DConvexShape](index.html#-786369621%2FClasslikes%2F-134779887) = [ConvexGeometricShape](../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[Euclidean2DPosition](../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](-euclidean2-d-transformation/index.html)><br>A convex euclidean shape in a bidimensional environment. |
| [Euclidean2DShape](index.html#1496739300%2FClasslikes%2F-134779887) | [jvm]<br>typealias [Euclidean2DShape](index.html#1496739300%2FClasslikes%2F-134779887) = [GeometricShape](../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.html)<[Euclidean2DPosition](../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](-euclidean2-d-transformation/index.html)><br>Defines an euclidean shape in a bidimensional space. |
| [Euclidean2DShapeFactory](-euclidean2-d-shape-factory/index.html) | [jvm]<br>interface [Euclidean2DShapeFactory](-euclidean2-d-shape-factory/index.html) : [GeometricShapeFactory](../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/index.html)<[Euclidean2DPosition](../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](-euclidean2-d-transformation/index.html)> <br>Defines a factory of [GeometricShape](../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.html) for a bidimensional euclidean space. |
| [Euclidean2DTransformation](-euclidean2-d-transformation/index.html) | [jvm]<br>interface [Euclidean2DTransformation](-euclidean2-d-transformation/index.html) : [GeometricTransformation](../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[Euclidean2DPosition](../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)> <br>Defines the possible transformations for a [it.unibo.alchemist.model.interfaces.geometry.GeometricShape](../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.html) in a bidimensional euclidean space. |
| [Intersection2D](-intersection2-d/index.html) | [jvm]<br>sealed class [Intersection2D](-intersection2-d/index.html)<out [V](-intersection2-d/index.html)><br>Describes the result an intersection operation in an euclidean 2D space. |
| [Line2D](-line2-d/index.html) | [jvm]<br>interface [Line2D](-line2-d/index.html)<[P](-line2-d/index.html) : [Vector2D](../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.html)<[P](-line2-d/index.html)>><br>Defines a straight line in a cartesian plane. |
| [MutableConvexPolygon](-mutable-convex-polygon/index.html) | [jvm]<br>interface [MutableConvexPolygon](-mutable-convex-polygon/index.html) : [ConvexPolygon](-convex-polygon/index.html)<br>A mutable [ConvexPolygon](-convex-polygon/index.html). |
| [Segment2D](-segment2-d/index.html) | [jvm]<br>interface [Segment2D](-segment2-d/index.html)<[P](-segment2-d/index.html) : [Vector2D](../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.html)<[P](-segment2-d/index.html)>><br>Defines a line segment in a cartesian plane, endpoints are included. |


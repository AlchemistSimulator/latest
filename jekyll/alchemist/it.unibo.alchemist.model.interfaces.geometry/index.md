---
title: it.unibo.alchemist.model.interfaces.geometry
---
//[alchemist](../../index.html)/[it.unibo.alchemist.model.interfaces.geometry](index.html)



# Package it.unibo.alchemist.model.interfaces.geometry



## Types


| Name | Summary |
|---|---|
| [ConvexGeometricShape](-convex-geometric-shape/index.html) | [jvm]<br>interface [ConvexGeometricShape](-convex-geometric-shape/index.html)<[V](-convex-geometric-shape/index.html) : [Vector](-vector/index.html)<[V](-convex-geometric-shape/index.html)>, [A](-convex-geometric-shape/index.html) : [GeometricTransformation](-geometric-transformation/index.html)<[V](-convex-geometric-shape/index.html)>> : [GeometricShape](-geometric-shape/index.html)<[V](-convex-geometric-shape/index.html), [A](-convex-geometric-shape/index.html)> <br>A convex [GeometricShape](-geometric-shape/index.html). |
| [GeometricShape](-geometric-shape/index.html) | [jvm]<br>interface [GeometricShape](-geometric-shape/index.html)<[S](-geometric-shape/index.html) : [Vector](-vector/index.html)<[S](-geometric-shape/index.html)>, [A](-geometric-shape/index.html) : [GeometricTransformation](-geometric-transformation/index.html)<[S](-geometric-shape/index.html)>> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>Models a generic shape. |
| [GeometricShapeFactory](-geometric-shape-factory/index.html) | [jvm]<br>interface [GeometricShapeFactory](-geometric-shape-factory/index.html)<[S](-geometric-shape-factory/index.html) : [Vector](-vector/index.html)<[S](-geometric-shape-factory/index.html)>, [A](-geometric-shape-factory/index.html) : [GeometricTransformation](-geometric-transformation/index.html)<[S](-geometric-shape-factory/index.html)>> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>Generic factory for [GeometricShape](-geometric-shape/index.html). |
| [GeometricTransformation](-geometric-transformation/index.html) | [jvm]<br>interface [GeometricTransformation](-geometric-transformation/index.html)<[S](-geometric-transformation/index.html) : [Vector](-vector/index.html)<[S](-geometric-transformation/index.html)>><br>Defines a generic transformation of a generic shape. |
| [InfluenceSphere](-influence-sphere/index.html) | [jvm]<br>interface [InfluenceSphere](-influence-sphere/index.html)<br>Area inside which nodes exert an influence on each other. |
| [Vector](-vector/index.html) | [jvm]<br>interface [Vector](-vector/index.html)<[S](-vector/index.html) : [Vector](-vector/index.html)<[S](-vector/index.html)>><br>A generic vector in a multidimensional space. |
| [Vector2D](-vector2-d/index.html) | [jvm]<br>interface [Vector2D](-vector2-d/index.html)<[P](-vector2-d/index.html) : [Vector2D](-vector2-d/index.html)<[P](-vector2-d/index.html)>> : [Vector](-vector/index.html)<[P](-vector2-d/index.html)> <br>Bidimensional vector with [x](-vector2-d/x.html) and [y](-vector2-d/y.html) coordinates. |


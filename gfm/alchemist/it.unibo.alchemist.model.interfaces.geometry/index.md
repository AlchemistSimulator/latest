//[alchemist](../../index.md)/[it.unibo.alchemist.model.interfaces.geometry](index.md)

# Package it.unibo.alchemist.model.interfaces.geometry

## Types

| Name | Summary |
|---|---|
| [ConvexGeometricShape](-convex-geometric-shape/index.md) | [jvm]<br>interface [ConvexGeometricShape](-convex-geometric-shape/index.md)<[V](-convex-geometric-shape/index.md) : [Vector](-vector/index.md)<[V](-convex-geometric-shape/index.md)>, [A](-convex-geometric-shape/index.md) : [GeometricTransformation](-geometric-transformation/index.md)<[V](-convex-geometric-shape/index.md)>> : [GeometricShape](-geometric-shape/index.md)<[V](-convex-geometric-shape/index.md), [A](-convex-geometric-shape/index.md)> <br>A convex [GeometricShape](-geometric-shape/index.md). |
| [GeometricShape](-geometric-shape/index.md) | [jvm]<br>interface [GeometricShape](-geometric-shape/index.md)<[S](-geometric-shape/index.md) : [Vector](-vector/index.md)<[S](-geometric-shape/index.md)>, [A](-geometric-shape/index.md) : [GeometricTransformation](-geometric-transformation/index.md)<[S](-geometric-shape/index.md)>> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>Models a generic shape. |
| [GeometricShapeFactory](-geometric-shape-factory/index.md) | [jvm]<br>interface [GeometricShapeFactory](-geometric-shape-factory/index.md)<[S](-geometric-shape-factory/index.md) : [Vector](-vector/index.md)<[S](-geometric-shape-factory/index.md)>, [A](-geometric-shape-factory/index.md) : [GeometricTransformation](-geometric-transformation/index.md)<[S](-geometric-shape-factory/index.md)>> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>Generic factory for [GeometricShape](-geometric-shape/index.md). |
| [GeometricTransformation](-geometric-transformation/index.md) | [jvm]<br>interface [GeometricTransformation](-geometric-transformation/index.md)<[S](-geometric-transformation/index.md) : [Vector](-vector/index.md)<[S](-geometric-transformation/index.md)>><br>Defines a generic transformation of a generic shape. |
| [InfluenceSphere](-influence-sphere/index.md) | [jvm]<br>interface [InfluenceSphere](-influence-sphere/index.md)<br>Area inside which nodes exert an influence on each other. |
| [Vector](-vector/index.md) | [jvm]<br>interface [Vector](-vector/index.md)<[S](-vector/index.md) : [Vector](-vector/index.md)<[S](-vector/index.md)>><br>A generic vector in a multidimensional space. |
| [Vector2D](-vector2-d/index.md) | [jvm]<br>interface [Vector2D](-vector2-d/index.md)<[P](-vector2-d/index.md) : [Vector2D](-vector2-d/index.md)<[P](-vector2-d/index.md)>> : [Vector](-vector/index.md)<[P](-vector2-d/index.md)> <br>Bidimensional vector with [x](-vector2-d/x.md) and [y](-vector2-d/y.md) coordinates. |

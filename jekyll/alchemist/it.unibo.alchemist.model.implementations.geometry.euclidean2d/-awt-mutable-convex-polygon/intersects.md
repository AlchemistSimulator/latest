---
title: intersects
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.geometry.euclidean2d](../index.html)/[AwtMutableConvexPolygon](index.html)/[intersects](intersects.html)



# intersects



[jvm]\
open override fun [intersects](intersects.html)(shape: [Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)



Delegated to [java.awt.geom.Area](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Area.html), this is accurate and does not consider adjacent shapes to be intersecting.





[jvm]\
open override fun [intersects](intersects.html)(other: [Euclidean2DShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.html#1496739300%2FClasslikes%2F-134779887)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)



Delegated to AwtEuclidean2DShape unless [other](intersects.html) is [AwtShapeCompatible](../../it.unibo.alchemist.model.implementations.geometry/-awt-shape-compatible/index.html), in which case [intersects](intersects.html) is used so as to guarantee maximum accuracy.





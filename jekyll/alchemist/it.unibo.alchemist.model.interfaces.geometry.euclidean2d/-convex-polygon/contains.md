---
title: contains
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d](../index.html)/[ConvexPolygon](index.html)/[contains](contains.html)



# contains



[jvm]\
abstract override fun [contains](contains.html)(vector: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)



Checks if the polygon contains a vector (= a point). The definition of insideness may vary depending on the implementation, this may affect the outcome for points lying on the polygon's boundary. For accurate operations see [containsBoundaryIncluded](contains-boundary-included.html) and [containsBoundaryExcluded](contains-boundary-excluded.html).



## Parameters


jvm

| | |
|---|---|
| vector | the vector (= point) |





[jvm]\
abstract fun [contains](contains.html)(shape: [Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)



Checks if the polygon contains a polygonal [java.awt.Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html) (i.e. without curved segments). A polygonal shape is contained in a polygon if all of its points are contained in (or lie on the boundary of) the latter.



## Parameters


jvm

| | |
|---|---|
| shape | the polygonal shape |





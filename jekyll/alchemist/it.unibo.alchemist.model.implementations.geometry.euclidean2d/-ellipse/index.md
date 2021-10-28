---
title: Ellipse
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.geometry.euclidean2d](../index.html)/[Ellipse](index.html)



# Ellipse



[jvm]\
class [Ellipse](index.html)(**ellipse**: [Ellipse2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Ellipse2D.html)) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html)> , [AwtShapeCompatible](../../it.unibo.alchemist.model.implementations.geometry/-awt-shape-compatible/index.html)

Adapter of [java.awt.geom.Ellipse2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Ellipse2D.html) to [Euclidean2DConvexShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.html#-786369621%2FClasslikes%2F-134779887).



## Constructors


| | |
|---|---|
| [Ellipse](-ellipse.html) | [jvm]<br>fun [Ellipse](-ellipse.html)(ellipse: [Ellipse2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Ellipse2D.html)) |


## Functions


| Name | Summary |
|---|---|
| [asAwtShape](as-awt-shape.html) | [jvm]<br>open override fun [asAwtShape](as-awt-shape.html)(): [Ellipse2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Ellipse2D.html) |
| [contains](contains.html) | [jvm]<br>open override fun [contains](contains.html)(vector: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [intersects](intersects.html) | [jvm]<br>open override fun [intersects](intersects.html)(other: [Euclidean2DShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.html#1496739300%2FClasslikes%2F-134779887)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [transformed](transformed.html) | [jvm]<br>open override fun [transformed](transformed.html)(transformation: [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html)> |


## Properties


| Name | Summary |
|---|---|
| [centroid](centroid.html) | [jvm]<br>open override val [centroid](centroid.html): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html) |
| [diameter](diameter.html) | [jvm]<br>open override val [diameter](diameter.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [radius](index.html#1089834465%2FProperties%2F-134779887) | [jvm]<br>open val [radius](index.html#1089834465%2FProperties%2F-134779887): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |


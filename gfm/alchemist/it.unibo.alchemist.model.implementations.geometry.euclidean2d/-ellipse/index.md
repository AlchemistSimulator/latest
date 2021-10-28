//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.geometry.euclidean2d](../index.md)/[Ellipse](index.md)

# Ellipse

[jvm]\
class [Ellipse](index.md)(**ellipse**: [Ellipse2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Ellipse2D.html)) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.md)> , [AwtShapeCompatible](../../it.unibo.alchemist.model.implementations.geometry/-awt-shape-compatible/index.md)

Adapter of [java.awt.geom.Ellipse2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Ellipse2D.html) to [Euclidean2DConvexShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.md#-786369621%2FClasslikes%2F-267951372).

## Constructors

| | |
|---|---|
| [Ellipse](-ellipse.md) | [jvm]<br>fun [Ellipse](-ellipse.md)(ellipse: [Ellipse2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Ellipse2D.html)) |

## Functions

| Name | Summary |
|---|---|
| [asAwtShape](as-awt-shape.md) | [jvm]<br>open override fun [asAwtShape](as-awt-shape.md)(): [Ellipse2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Ellipse2D.html) |
| [contains](contains.md) | [jvm]<br>open override fun [contains](contains.md)(vector: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [intersects](intersects.md) | [jvm]<br>open override fun [intersects](intersects.md)(other: [Euclidean2DShape](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/index.md#1496739300%2FClasslikes%2F-267951372)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [transformed](transformed.md) | [jvm]<br>open override fun [transformed](transformed.md)(transformation: [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.md).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.md)> |

## Properties

| Name | Summary |
|---|---|
| [centroid](centroid.md) | [jvm]<br>open override val [centroid](centroid.md): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md) |
| [diameter](diameter.md) | [jvm]<br>open override val [diameter](diameter.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [radius](index.md#1089834465%2FProperties%2F-267951372) | [jvm]<br>open val [radius](index.md#1089834465%2FProperties%2F-267951372): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |

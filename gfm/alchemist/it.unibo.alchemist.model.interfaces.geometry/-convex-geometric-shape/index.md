//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces.geometry](../index.md)/[ConvexGeometricShape](index.md)

# ConvexGeometricShape

[jvm]\
interface [ConvexGeometricShape](index.md)<[V](index.md) : [Vector](../-vector/index.md)<[V](index.md)>, [A](index.md) : [GeometricTransformation](../-geometric-transformation/index.md)<[V](index.md)>> : [GeometricShape](../-geometric-shape/index.md)<[V](index.md), [A](index.md)> 

A convex [GeometricShape](../-geometric-shape/index.md).

This interface models a property instead of an object, this may be unusual but consider it as a contract: interfaces are often said to be contracts the implementor has to comply, the contract defined by this interface implies convexity.

## Functions

| Name | Summary |
|---|---|
| [contains](../-geometric-shape/contains.md) | [jvm]<br>abstract fun [contains](../-geometric-shape/contains.md)(vector: [V](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [intersects](../-geometric-shape/intersects.md) | [jvm]<br>abstract fun [intersects](../-geometric-shape/intersects.md)(other: [GeometricShape](../-geometric-shape/index.md)<[V](index.md), [A](index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [transformed](../-geometric-shape/transformed.md) | [jvm]<br>abstract fun [transformed](../-geometric-shape/transformed.md)(transformation: [A](index.md).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [GeometricShape](../-geometric-shape/index.md)<[V](index.md), [A](index.md)> |

## Properties

| Name | Summary |
|---|---|
| [centroid](index.md#-1603412397%2FProperties%2F-267951372) | [jvm]<br>abstract val [centroid](index.md#-1603412397%2FProperties%2F-267951372): [V](index.md) |
| [diameter](index.md#-98529242%2FProperties%2F-267951372) | [jvm]<br>abstract val [diameter](index.md#-98529242%2FProperties%2F-267951372): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [radius](index.md#-393513663%2FProperties%2F-267951372) | [jvm]<br>open val [radius](index.md#-393513663%2FProperties%2F-267951372): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |

## Inheritors

| Name |
|---|
| [Ellipse](../../it.unibo.alchemist.model.implementations.geometry.euclidean2d/-ellipse/index.md) |
| [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md) |

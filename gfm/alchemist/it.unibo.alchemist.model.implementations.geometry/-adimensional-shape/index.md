//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.geometry](../index.md)/[AdimensionalShape](index.md)

# AdimensionalShape

[jvm]\
class [AdimensionalShape](index.md)<[S](index.md) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[S](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[S](index.md)>>(**centroid**: [S](index.md)) : [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.md)<[S](index.md), [A](index.md)> 

A special shape which does not occupy space and does not intersect with any other, not even with itself. It also ignores any transformation.

## Constructors

| | |
|---|---|
| [AdimensionalShape](-adimensional-shape.md) | [jvm]<br>fun <[S](index.md) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[S](index.md)>> [AdimensionalShape](-adimensional-shape.md)(centroid: [S](index.md)) |

## Functions

| Name | Summary |
|---|---|
| [contains](contains.md) | [jvm]<br>open override fun [contains](contains.md)(vector: [S](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [intersects](intersects.md) | [jvm]<br>open override fun [intersects](intersects.md)(other: [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.md)<[S](index.md), [A](index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [transformed](transformed.md) | [jvm]<br>open override fun [transformed](transformed.md)(transformation: [A](index.md).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [AdimensionalShape](index.md)<[S](index.md), [A](index.md)><br>Any transformation is ignored. |

## Properties

| Name | Summary |
|---|---|
| [centroid](centroid.md) | [jvm]<br>open override val [centroid](centroid.md): [S](index.md) |
| [diameter](diameter.md) | [jvm]<br>open override val [diameter](diameter.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0 |
| [radius](index.md#794852178%2FProperties%2F-267951372) | [jvm]<br>open val [radius](index.md#794852178%2FProperties%2F-267951372): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |

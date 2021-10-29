---
title: AdimensionalShape
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.geometry](../index.html)/[AdimensionalShape](index.html)



# AdimensionalShape



[jvm]\
class [AdimensionalShape](index.html)<[S](index.html) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[S](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[S](index.html)>>(**centroid**: [S](index.html)) : [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.html)<[S](index.html), [A](index.html)> 

A special shape which does not occupy space and does not intersect with any other, not even with itself. It also ignores any transformation.



## Constructors


| | |
|---|---|
| [AdimensionalShape](-adimensional-shape.html) | [jvm]<br>fun <[S](index.html) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[S](index.html)>> [AdimensionalShape](-adimensional-shape.html)(centroid: [S](index.html)) |


## Functions


| Name | Summary |
|---|---|
| [contains](contains.html) | [jvm]<br>open override fun [contains](contains.html)(vector: [S](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [intersects](intersects.html) | [jvm]<br>open override fun [intersects](intersects.html)(other: [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.html)<[S](index.html), [A](index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [transformed](transformed.html) | [jvm]<br>open override fun [transformed](transformed.html)(transformation: [A](index.html).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [AdimensionalShape](index.html)<[S](index.html), [A](index.html)><br>Any transformation is ignored. |


## Properties


| Name | Summary |
|---|---|
| [centroid](centroid.html) | [jvm]<br>open override val [centroid](centroid.html): [S](index.html) |
| [diameter](diameter.html) | [jvm]<br>open override val [diameter](diameter.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0 |
| [radius](index.html#794852178%2FProperties%2F-134779887) | [jvm]<br>open val [radius](index.html#794852178%2FProperties%2F-134779887): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |


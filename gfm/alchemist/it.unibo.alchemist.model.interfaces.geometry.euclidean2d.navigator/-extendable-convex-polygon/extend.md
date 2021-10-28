//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d.navigator](../index.md)/[ExtendableConvexPolygon](index.md)/[extend](extend.md)

# extend

[jvm]\
abstract fun [extend](extend.md)(step: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Extends the polygon in each direction: each edge is given a chance to advance.

## Parameters

jvm

| | |
|---|---|
| step | the length of the vector that will be used to advance each edge, negative values are supported and will shrink the polygon instead of extending it. |

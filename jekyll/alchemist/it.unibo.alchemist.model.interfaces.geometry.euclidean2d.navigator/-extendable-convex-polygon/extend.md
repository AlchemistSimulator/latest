---
title: extend
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d.navigator](../index.html)/[ExtendableConvexPolygon](index.html)/[extend](extend.html)



# extend



[jvm]\
abstract fun [extend](extend.html)(step: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)



Extends the polygon in each direction: each edge is given a chance to advance.



## Parameters


jvm

| | |
|---|---|
| step | the length of the vector that will be used to advance each edge, negative values are supported and will shrink the polygon instead of extending it. |





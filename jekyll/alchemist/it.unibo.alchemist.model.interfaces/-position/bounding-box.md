---
title: boundingBox
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Position](index.html)/[boundingBox](bounding-box.html)



# boundingBox



[jvm]\
abstract fun [boundingBox](bounding-box.html)(range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[P](index.html)>



Given a range, produces N coordinates, representing the N opposite vertices of the hypercube having the current coordinate as center and circumscribing the N-sphere defined by the range. In the case of two dimensional coordinates, it must return the opposite vertices of the square circumscribing the circle with center in this position and radius range.



#### Return



the vertices of the circumscribed hypercube



## Parameters


jvm

| | |
|---|---|
| range | the radius of the hypersphere |





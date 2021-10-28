//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Position](index.md)/[boundingBox](bounding-box.md)

# boundingBox

[jvm]\
abstract fun [boundingBox](bounding-box.md)(range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[P](index.md)>

Given a range, produces N coordinates, representing the N opposite vertices of the hypercube having the current coordinate as center and circumscribing the N-sphere defined by the range. In the case of two dimensional coordinates, it must return the opposite vertices of the square circumscribing the circle with center in this position and radius range.

#### Return

the vertices of the circumscribed hypercube

## Parameters

jvm

| | |
|---|---|
| range | the radius of the hypersphere |

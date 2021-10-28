//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d](../index.md)/[Euclidean2DShapeFactory](index.md)/[circleSector](circle-sector.md)

# circleSector

[jvm]\
abstract fun [circleSector](circle-sector.md)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), angle: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), heading: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Euclidean2DShape](../index.md#1496739300%2FClasslikes%2F-267951372)

A circle sector is the portion of a disk enclosed by two radii and an arc and it extends in the first and second axis by its radius and angle.

#### Return

the shape

## Parameters

jvm

| | |
|---|---|
| radius | the radius of the circle from which the sector is extracted |
| angle | the angle of the arc in radians, it determines its dimension in the second axis |
| heading | the angle in radians of the median segment which bisects the sector.     It's used to determine the sector's heading. |

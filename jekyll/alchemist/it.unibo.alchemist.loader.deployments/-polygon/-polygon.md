---
title: Polygon
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.deployments](../index.html)/[Polygon](index.html)/[Polygon](-polygon.html)



# Polygon



[jvm]\
fun <[P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](index.html)>> [Polygon](-polygon.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<*, [P](index.html)>, randomGenerator: RandomGenerator, nodes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), pointsInput: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<*>)



## Parameters


jvm

| | |
|---|---|
| nodes | the count of nodes that need to get displaced inside the polygon |
| pointsInput | the points of the polygon. The class does not check for "malformed" polygons (e.g. with intersections). If the provided points do not represent a valid polygon in bidimensional space, the behaviour of this class is undefined. There polygon is closed automatically (there is no need to pass the first point also as last element). |





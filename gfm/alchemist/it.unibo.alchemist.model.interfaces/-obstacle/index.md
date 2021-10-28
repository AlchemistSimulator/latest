//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Obstacle](index.md)

# Obstacle

[jvm]\
interface [Obstacle](index.md)<[V](index.md) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[V](index.md)>> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

A generic obstacle in a vector space.

## Parameters

jvm

| | |
|---|---|
| V | the vector type for the space in which this obstacle is placed. |

## Functions

| Name | Summary |
|---|---|
| [nearestIntersection](nearest-intersection.md) | [jvm]<br>abstract fun [nearestIntersection](nearest-intersection.md)(start: [V](index.md), end: [V](index.md)): [V](index.md)<br>Given a vector (represented as a starting point and an end point), computes the intersection point between the vector and the obstacle nearest to the vector's starting point. |
| [next](next.md) | [jvm]<br>abstract fun [next](next.md)(start: [V](index.md), end: [V](index.md)): [V](index.md)<br>Given a vector (starting point and end point) representing a requested move, this method computes a new end point, representing a cut version of the initial vector, modified in such a way that the end point is outside the obstacle. |

## Properties

| Name | Summary |
|---|---|
| [id](id.md) | [jvm]<br>abstract val [id](id.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The id for this obstacle. |

## Inheritors

| Name |
|---|
| [Obstacle2D](../-obstacle2-d/index.md) |

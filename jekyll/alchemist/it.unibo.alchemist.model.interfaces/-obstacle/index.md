---
title: Obstacle
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Obstacle](index.html)



# Obstacle



[jvm]\
interface [Obstacle](index.html)<[V](index.html) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[V](index.html)>> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

A generic obstacle in a vector space.



## Parameters


jvm

| | |
|---|---|
| V | the vector type for the space in which this obstacle is placed. |



## Functions


| Name | Summary |
|---|---|
| [nearestIntersection](nearest-intersection.html) | [jvm]<br>abstract fun [nearestIntersection](nearest-intersection.html)(start: [V](index.html), end: [V](index.html)): [V](index.html)<br>Given a vector (represented as a starting point and an end point), computes the intersection point between the vector and the obstacle nearest to the vector's starting point. |
| [next](next.html) | [jvm]<br>abstract fun [next](next.html)(start: [V](index.html), end: [V](index.html)): [V](index.html)<br>Given a vector (starting point and end point) representing a requested move, this method computes a new end point, representing a cut version of the initial vector, modified in such a way that the end point is outside the obstacle. |


## Properties


| Name | Summary |
|---|---|
| [id](id.html) | [jvm]<br>abstract val [id](id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The id for this obstacle. |


## Inheritors


| Name |
|---|
| [Obstacle2D](../-obstacle2-d/index.html) |


---
title: next
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Obstacle](index.html)/[next](next.html)



# next



[jvm]\
abstract fun [next](next.html)(start: [V](index.html), end: [V](index.html)): [V](index.html)



Given a vector (starting point and end point) representing a requested move, this method computes a new end point, representing a cut version of the initial vector, modified in such a way that the end point is outside the obstacle.



#### Return



the intersection point between the vector and the obstacle nearest to the vector's starting point.



## Parameters


jvm

| | |
|---|---|
| start | starting point of the vector |
| end | ending point of the vector |





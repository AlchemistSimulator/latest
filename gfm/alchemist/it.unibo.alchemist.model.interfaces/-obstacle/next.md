//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Obstacle](index.md)/[next](next.md)

# next

[jvm]\
abstract fun [next](next.md)(start: [V](index.md), end: [V](index.md)): [V](index.md)

Given a vector (starting point and end point) representing a requested move, this method computes a new end point, representing a cut version of the initial vector, modified in such a way that the end point is outside the obstacle.

#### Return

the intersection point between the vector and the obstacle nearest to the vector's starting point.

## Parameters

jvm

| | |
|---|---|
| start | starting point of the vector |
| end | ending point of the vector |

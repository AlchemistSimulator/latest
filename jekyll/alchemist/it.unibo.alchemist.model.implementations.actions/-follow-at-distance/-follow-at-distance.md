---
title: FollowAtDistance
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[FollowAtDistance](index.html)/[FollowAtDistance](-follow-at-distance.html)



# FollowAtDistance



[jvm]\
fun <[T](index.html)> [FollowAtDistance](-follow-at-distance.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>, env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>, target: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), distance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), speed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))



## Parameters


jvm

| | |
|---|---|
|  | <T> concentration type |
| env | the environment containing the nodes |
| node | the follower |
| reaction | the reaction hosting this action |
| target | molecule from which to read the destination to follow in the form of coordinates or a tuple |
| distance | the distance to keep from the destination |
| speed | the maximum speed |





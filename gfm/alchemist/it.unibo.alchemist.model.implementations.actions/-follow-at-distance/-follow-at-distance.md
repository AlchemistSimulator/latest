//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[FollowAtDistance](index.md)/[FollowAtDistance](-follow-at-distance.md)

# FollowAtDistance

[jvm]\
fun <[T](index.md)> [FollowAtDistance](-follow-at-distance.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>, env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>, target: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), distance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), speed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

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

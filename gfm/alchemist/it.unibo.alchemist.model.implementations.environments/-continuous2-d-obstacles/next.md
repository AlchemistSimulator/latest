//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.environments](../index.md)/[Continuous2DObstacles](index.md)/[next](next.md)

# next

[jvm]\

@NotNull()

fun [next](next.md)(@NotNull()current: @NotNull()[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), @NotNull()desired: @NotNull()[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)): @NotNull()[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)

[jvm]\
fun [next](next.md)(ox: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), oy: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), nx: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), ny: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)

This method must calculate the ABSOLUTE next allowed position given the current position and the position in which the node wants to move. For example, if your node is in position [2,3], wants to move to [3,4] but the next allowed position (because, e.g., of physical obstacles) is [2.5,3.5], the result must be a Position containing coordinates [2.5,3.5].

#### Return

the next allowed position, where the node can actually move. This position MUST be considered as a vector whose start point is in [ox, oy].

## Parameters

jvm

| | |
|---|---|
| ox | The current X position |
| oy | The current Y position |
| nx | The requested X position |
| ny | The requested Y position |

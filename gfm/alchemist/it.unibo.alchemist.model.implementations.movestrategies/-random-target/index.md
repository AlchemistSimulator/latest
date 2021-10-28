//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.movestrategies](../index.md)/[RandomTarget](index.md)

# RandomTarget

[jvm]\
class [RandomTarget](index.md)<[T](index.md)>(**environment**: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>, **getCurrentPosition**: () -> [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), **makePosition**: ([Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) -> [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), **directionRng**: RandomGenerator, **distanceDistribution**: RealDistribution) : [ChangeTargetOnCollision](../-change-target-on-collision/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)> 

Selects a target based on a random direction extracted from directionRng, and a random distance extracted from distanceDistribution. getCurrentPosition should return the current position of the object to move. [T](index.md) is the type of the concentration of the node.

## Constructors

| | |
|---|---|
| [RandomTarget](-random-target.md) | [jvm]<br>fun <[T](index.md)> [RandomTarget](-random-target.md)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, directionRng: RandomGenerator, distanceDistribution: RealDistribution)<br>Handy constructor for Alchemist where the object to move is a node in the env. |
| [RandomTarget](-random-target.md) | [jvm]<br>fun <[T](index.md)> [RandomTarget](-random-target.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>, getCurrentPosition: () -> [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), makePosition: ([Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) -> [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), directionRng: RandomGenerator, distanceDistribution: RealDistribution) |

## Functions

| Name | Summary |
|---|---|
| [getTarget](../-change-target-on-collision/get-target.md) | [jvm]<br>open override fun [getTarget](../-change-target-on-collision/get-target.md)(): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md) |

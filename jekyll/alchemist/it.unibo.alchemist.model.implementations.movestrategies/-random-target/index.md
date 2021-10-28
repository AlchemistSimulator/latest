---
title: RandomTarget
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.movestrategies](../index.html)/[RandomTarget](index.html)



# RandomTarget



[jvm]\
class [RandomTarget](index.html)<[T](index.html)>(**environment**: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>, **getCurrentPosition**: () -> [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), **makePosition**: ([Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) -> [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), **directionRng**: RandomGenerator, **distanceDistribution**: RealDistribution) : [ChangeTargetOnCollision](../-change-target-on-collision/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)> 

Selects a target based on a random direction extracted from directionRng, and a random distance extracted from distanceDistribution. getCurrentPosition should return the current position of the object to move. [T](index.html) is the type of the concentration of the node.



## Constructors


| | |
|---|---|
| [RandomTarget](-random-target.html) | [jvm]<br>fun <[T](index.html)> [RandomTarget](-random-target.html)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, directionRng: RandomGenerator, distanceDistribution: RealDistribution)<br>Handy constructor for Alchemist where the object to move is a node in the env. |
| [RandomTarget](-random-target.html) | [jvm]<br>fun <[T](index.html)> [RandomTarget](-random-target.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>, getCurrentPosition: () -> [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), makePosition: ([Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) -> [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), directionRng: RandomGenerator, distanceDistribution: RealDistribution) |


## Functions


| Name | Summary |
|---|---|
| [getTarget](../-change-target-on-collision/get-target.html) | [jvm]<br>open override fun [getTarget](../-change-target-on-collision/get-target.html)(): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html) |


---
title: it.unibo.alchemist.model.implementations.movestrategies
---
//[alchemist](../../index.html)/[it.unibo.alchemist.model.implementations.movestrategies](index.html)



# Package it.unibo.alchemist.model.implementations.movestrategies



## Types


| Name | Summary |
|---|---|
| [AbstractStrategyWithGPS](-abstract-strategy-with-g-p-s/index.html) | [jvm]<br>abstract class [AbstractStrategyWithGPS](-abstract-strategy-with-g-p-s/index.html) : [ObjectWithGPS](../it.unibo.alchemist.model.interfaces/-object-with-g-p-s/index.html)<br>basic move strategy that use a [GPSTrace](../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.html). |
| [ChangeTargetOnCollision](-change-target-on-collision/index.html) | [jvm]<br>abstract class [ChangeTargetOnCollision](-change-target-on-collision/index.html)<[P](-change-target-on-collision/index.html) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](-change-target-on-collision/index.html)>>(**getCurrentPosition**: () -> [P](-change-target-on-collision/index.html)) : [TargetSelectionStrategy](../it.unibo.alchemist.model.interfaces.movestrategies/-target-selection-strategy/index.html)<[P](-change-target-on-collision/index.html)> <br>Base class for [TargetSelectionStrategy](../it.unibo.alchemist.model.interfaces.movestrategies/-target-selection-strategy/index.html) offering automatic target change on collision and utilities for initialization. |
| [RandomTarget](-random-target/index.html) | [jvm]<br>class [RandomTarget](-random-target/index.html)<[T](-random-target/index.html)>(**environment**: [Environment](../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](-random-target/index.html), [Euclidean2DPosition](../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>, **getCurrentPosition**: () -> [Euclidean2DPosition](../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), **makePosition**: ([Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) -> [Euclidean2DPosition](../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), **directionRng**: RandomGenerator, **distanceDistribution**: RealDistribution) : [ChangeTargetOnCollision](-change-target-on-collision/index.html)<[Euclidean2DPosition](../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)> <br>Selects a target based on a random direction extracted from directionRng, and a random distance extracted from distanceDistribution. |


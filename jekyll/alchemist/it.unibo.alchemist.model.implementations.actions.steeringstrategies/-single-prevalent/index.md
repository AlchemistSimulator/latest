---
title: SinglePrevalent
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions.steeringstrategies](../index.html)/[SinglePrevalent](index.html)



# SinglePrevalent



[jvm]\
class [SinglePrevalent](index.html)<[T](index.html), [N](index.html) : [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html)>(**environment**: [Euclidean2DEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment-with-graph/index.html)<*, [T](index.html), [N](index.html), *>, **pedestrian**: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.html)<[T](index.html)>, **prevalent**: SteeringActions<[T](index.html)>.() -> [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.html#-517309547%2FClasslikes%2F-134779887)<[T](index.html), *, *, [N](index.html), *>, **toleranceAngle**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **alpha**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **maxWalk**: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **maxWalkRatio**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **delta**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [Weighted](../-weighted/index.html)<[T](index.html)> 

A [SteeringStrategy](../../it.unibo.alchemist.model.interfaces/-steering-strategy/index.html) in which one action is prevalent. Only [NavigationAction](../../it.unibo.alchemist.model.interfaces/-navigation-action/index.html)s can be prevalent, because they guarantee to navigate the environment consciously (e.g. without getting stuck in obstacles). The purpose of this strategy is to linearly combine the potentially contrasting forces to which the pedestrian is subject, while maintaining that warranty. Such forces are combined as follows: let f be the prevalent force,



<ul><li>if f leads the pedestrian outside the room (= environment's area) he/she is into, no combination is performed and f is used as it is. This because crossing doors can be a thorny issue and we don't want to introduce disturbing forces.</li><li>Otherwise, a linear combination is performed: f is assigned unitary weight, all other forces are assigned weight w equal to the maximum value in 0,1 so that the resulting force:</li><li>forms with f an angle smaller than or equal to the specified toleranceAngle,</li><li>doesn't lead the pedestrian outside the current room. The idea is to decrease the intensity of non-prevalent forces until the resulting one enters in some tolerance sector defined by both the tolerance angle and the current room's boundary. With a suitable tolerance angle this allows to steer the pedestrian towards the target defined by the prevalent force, while using a trajectory which takes into account other urges as well. Finally, an exponential smoothing with the given alpha is applied to the resulting force in order to decrease oscillatory movements (this also known as shaking behavior).</li></ul>



## Parameters


jvm

| | |
|---|---|
| T | concentration type |
| N | type of nodes of the environment's graph. |



## Constructors


| | |
|---|---|
| [SinglePrevalent](-single-prevalent.html) | [jvm]<br>fun <[T](index.html), [N](index.html) : [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html)> [SinglePrevalent](-single-prevalent.html)(environment: [Euclidean2DEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment-with-graph/index.html)<*, [T](index.html), [N](index.html), *>, pedestrian: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.html)<[T](index.html)>, prevalent: SteeringActions<[T](index.html)>.() -> [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.html#-517309547%2FClasslikes%2F-134779887)<[T](index.html), *, *, [N](index.html), *>, toleranceAngle: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = DEFAULT_TOLERANCE_ANGLE, alpha: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = DEFAULT_ALPHA, maxWalk: () -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), maxWalkRatio: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = DEFAULT_MAX_WALK_RATIO, delta: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = DEFAULT_DELTA)<br>concentration type |


## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [computeNextPosition](compute-next-position.html) | [jvm]<br>open override fun [computeNextPosition](compute-next-position.html)(actions: SteeringActions<[T](index.html)>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)<br>[actions](compute-next-position.html) are partitioned in group steering actions and non-group steering actions. |
| [computeTarget](../-weighted/compute-target.html) | [jvm]<br>open override fun [computeTarget](../-weighted/compute-target.html)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)<br>If there's no [SteeringActionWithTarget](../../it.unibo.alchemist.model.interfaces/-steering-action-with-target/index.html) among the provided [actions](../-weighted/compute-target.html), a zero vector is returned. |


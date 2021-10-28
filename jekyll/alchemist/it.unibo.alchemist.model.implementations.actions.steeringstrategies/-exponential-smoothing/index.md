---
title: ExponentialSmoothing
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions.steeringstrategies](../index.html)/[ExponentialSmoothing](index.html)



# ExponentialSmoothing



[jvm]\
class [ExponentialSmoothing](index.html)<[V](index.html) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[V](index.html)>>(**alpha**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

Exponential smoothing is a trivial way of smoothing signals. Let s(t) be the smoothed signal at time t, given a discrete signal g: s(t) = alpha * g(t) + (1 - alpha) * s(t-1) s(0) = g(0)



## Constructors


| | |
|---|---|
| [ExponentialSmoothing](-exponential-smoothing.html) | [jvm]<br>fun [ExponentialSmoothing](-exponential-smoothing.html)(alpha: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |


## Functions


| Name | Summary |
|---|---|
| [apply](apply.html) | [jvm]<br>fun [apply](apply.html)(current: [V](index.html)): [V](index.html)<br>Applies the smoothing to the given force. |


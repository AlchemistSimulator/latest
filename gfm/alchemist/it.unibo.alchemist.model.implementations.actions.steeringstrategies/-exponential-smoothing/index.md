//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions.steeringstrategies](../index.md)/[ExponentialSmoothing](index.md)

# ExponentialSmoothing

[jvm]\
class [ExponentialSmoothing](index.md)<[V](index.md) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[V](index.md)>>(**alpha**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

Exponential smoothing is a trivial way of smoothing signals. Let s(t) be the smoothed signal at time t, given a discrete signal g: s(t) = alpha * g(t) + (1 - alpha) * s(t-1) s(0) = g(0)

## Constructors

| | |
|---|---|
| [ExponentialSmoothing](-exponential-smoothing.md) | [jvm]<br>fun [ExponentialSmoothing](-exponential-smoothing.md)(alpha: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |

## Functions

| Name | Summary |
|---|---|
| [apply](apply.md) | [jvm]<br>fun [apply](apply.md)(current: [V](index.md)): [V](index.md)<br>Applies the smoothing to the given force. |

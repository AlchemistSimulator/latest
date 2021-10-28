//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[SteeringStrategy](index.md)/[computeNextPosition](compute-next-position.md)

# computeNextPosition

[jvm]\
abstract fun [computeNextPosition](compute-next-position.md)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../-steering-action/index.md)<[T](index.md), [P](index.md)>>): [P](index.md)

Computes the next position starting from the steering actions the pedestrian obey to, in relative coordinates with respect to its current position.

## Parameters

jvm

| | |
|---|---|
| actions | the list of actions to combine. |

//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[CognitiveAgentArrive](index.md)/[CognitiveAgentArrive](-cognitive-agent-arrive.md)

# CognitiveAgentArrive

[jvm]\
fun <[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[P](index.md)>> [CognitiveAgentArrive](-cognitive-agent-arrive.md)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [P](index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>, pedestrian: [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.md)<[T](index.md), [P](index.md), [A](index.md)>, decelerationRadius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), arrivalTolerance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), vararg coordinates: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html))

[jvm]\
fun <[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[P](index.md)>> [CognitiveAgentArrive](-cognitive-agent-arrive.md)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [P](index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>, pedestrian: [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.md)<[T](index.md), [P](index.md), [A](index.md)>, decelerationRadius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), arrivalTolerance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), target: [P](index.md))

## Parameters

jvm

| | |
|---|---|
| env | the environment inside which the pedestrian moves. |
| reaction | the reaction which executes this action. |
| pedestrian | the owner of this action. |
| decelerationRadius | the distance from which the pedestrian starts to decelerate. |
| arrivalTolerance | the distance at which the pedestrian is considered arrived to the target. |
| target | the position the pedestrian moves towards. |

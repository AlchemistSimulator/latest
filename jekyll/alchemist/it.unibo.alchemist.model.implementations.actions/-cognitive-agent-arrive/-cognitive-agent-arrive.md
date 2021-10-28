---
title: CognitiveAgentArrive
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[CognitiveAgentArrive](index.html)/[CognitiveAgentArrive](-cognitive-agent-arrive.html)



# CognitiveAgentArrive



[jvm]\
fun <[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[P](index.html)>> [CognitiveAgentArrive](-cognitive-agent-arrive.html)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>, pedestrian: [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.html)<[T](index.html), [P](index.html), [A](index.html)>, decelerationRadius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), arrivalTolerance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), vararg coordinates: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html))





[jvm]\
fun <[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[P](index.html)>> [CognitiveAgentArrive](-cognitive-agent-arrive.html)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>, pedestrian: [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.html)<[T](index.html), [P](index.html), [A](index.html)>, decelerationRadius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), arrivalTolerance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), target: [P](index.html))



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





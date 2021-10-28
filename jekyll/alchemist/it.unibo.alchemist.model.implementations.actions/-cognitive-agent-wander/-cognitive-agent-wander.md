---
title: CognitiveAgentWander
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[CognitiveAgentWander](index.html)/[CognitiveAgentWander](-cognitive-agent-wander.html)



# CognitiveAgentWander



[jvm]\
fun <[T](index.html)> [CognitiveAgentWander](-cognitive-agent-wander.html)(environment: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.html)<[T](index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>, pedestrian: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.html)<[T](index.html)>, randomGenerator: RandomGenerator, offset: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))



## Parameters


jvm

| | |
|---|---|
| environment | the environment inside which the pedestrian moves. |
| pedestrian | the owner of this action. |
| randomGenerator | the simulation {@link RandomGenerator}. |
| offset | the distance from the pedestrian position of the center of the circle. |
| radius | the radius of the circle. |





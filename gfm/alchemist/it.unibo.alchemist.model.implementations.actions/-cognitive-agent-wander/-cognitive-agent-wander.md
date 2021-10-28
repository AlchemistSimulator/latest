//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[CognitiveAgentWander](index.md)/[CognitiveAgentWander](-cognitive-agent-wander.md)

# CognitiveAgentWander

[jvm]\
fun <[T](index.md)> [CognitiveAgentWander](-cognitive-agent-wander.md)(environment: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md)<[T](index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>, pedestrian: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.md)<[T](index.md)>, randomGenerator: RandomGenerator, offset: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

## Parameters

jvm

| | |
|---|---|
| environment | the environment inside which the pedestrian moves. |
| pedestrian | the owner of this action. |
| randomGenerator | the simulation {@link RandomGenerator}. |
| offset | the distance from the pedestrian position of the center of the circle. |
| radius | the radius of the circle. |

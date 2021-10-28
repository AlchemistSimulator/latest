//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[CognitiveAgentCombineSteering](index.md)/[CognitiveAgentCombineSteering](-cognitive-agent-combine-steering.md)

# CognitiveAgentCombineSteering

[jvm]\
fun <[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[P](index.md)>> [CognitiveAgentCombineSteering](-cognitive-agent-combine-steering.md)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [P](index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>, pedestrian: [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.md)<[T](index.md), [P](index.md), [A](index.md)>, actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.md)<[T](index.md), [P](index.md)>>, steerStrategy: [SteeringStrategy](../../it.unibo.alchemist.model.interfaces/-steering-strategy/index.md)<[T](index.md), [P](index.md)>)

## Parameters

jvm

| | |
|---|---|
| env | the environment inside which the pedestrian moves. |
| pedestrian | the owner of this action. |
| actions | the list of actions to combine to determine the pedestrian movement. |
| steerStrategy | the logic according to the steering actions are combined. |

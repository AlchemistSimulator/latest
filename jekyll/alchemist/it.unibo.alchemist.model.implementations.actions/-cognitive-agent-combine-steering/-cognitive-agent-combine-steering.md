---
title: CognitiveAgentCombineSteering
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[CognitiveAgentCombineSteering](index.html)/[CognitiveAgentCombineSteering](-cognitive-agent-combine-steering.html)



# CognitiveAgentCombineSteering



[jvm]\
fun <[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[P](index.html)>> [CognitiveAgentCombineSteering](-cognitive-agent-combine-steering.html)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>, pedestrian: [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.html)<[T](index.html), [P](index.html), [A](index.html)>, actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.html)<[T](index.html), [P](index.html)>>, steerStrategy: [SteeringStrategy](../../it.unibo.alchemist.model.interfaces/-steering-strategy/index.html)<[T](index.html), [P](index.html)>)



## Parameters


jvm

| | |
|---|---|
| env | the environment inside which the pedestrian moves. |
| pedestrian | the owner of this action. |
| actions | the list of actions to combine to determine the pedestrian movement. |
| steerStrategy | the logic according to the steering actions are combined. |





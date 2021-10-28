---
title: CognitiveAgentAvoidLayer
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[CognitiveAgentAvoidLayer](index.html)/[CognitiveAgentAvoidLayer](-cognitive-agent-avoid-layer.html)



# CognitiveAgentAvoidLayer



[jvm]\




@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()



fun [CognitiveAgentAvoidLayer](-cognitive-agent-avoid-layer.html)(environment: [Euclidean2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment/index.html)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>, pedestrian: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.html)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>, targetMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), viewDepth: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = Double.POSITIVE_INFINITY)



## Parameters


jvm

| | |
|---|---|
| environment | the environment inside which the pedestrian moves. |
| reaction | the reaction which executes this action. |
| pedestrian | the owner of this action. |
| targetMolecule | the {@link Molecule} you want to know the concentration in the different positions of the environment. |
| viewDepth | the depth of view of the pedestrian, defaults to infinity. |





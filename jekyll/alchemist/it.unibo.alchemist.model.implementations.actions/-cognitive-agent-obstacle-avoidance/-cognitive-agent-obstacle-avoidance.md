---
title: CognitiveAgentObstacleAvoidance
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[CognitiveAgentObstacleAvoidance](index.html)/[CognitiveAgentObstacleAvoidance](-cognitive-agent-obstacle-avoidance.html)



# CognitiveAgentObstacleAvoidance



[jvm]\
fun <[W](index.html) : [Obstacle2D](../../it.unibo.alchemist.model.interfaces/-obstacle2-d/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>, [T](index.html)> [CognitiveAgentObstacleAvoidance](-cognitive-agent-obstacle-avoidance.html)(env: [Environment2DWithObstacles](../../it.unibo.alchemist.model.interfaces.environments/-environment2-d-with-obstacles/index.html)<[W](index.html), [T](index.html)>, reaction: [SteeringBehavior](../../it.unibo.alchemist.model.implementations.reactions/-steering-behavior/index.html)<[T](index.html)>, pedestrian: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.html)<[T](index.html)>, proximityRange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))



## Parameters


jvm

| | |
|---|---|
| env | the environment inside which the pedestrian moves. |
| reaction | the reaction which executes this action. |
| pedestrian | the owner of this action. |
| proximityRange | the distance at which an obstacle is perceived by the pedestrian. |





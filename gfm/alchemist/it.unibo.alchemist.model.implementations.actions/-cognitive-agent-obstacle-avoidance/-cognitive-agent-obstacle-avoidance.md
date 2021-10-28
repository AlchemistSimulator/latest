//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[CognitiveAgentObstacleAvoidance](index.md)/[CognitiveAgentObstacleAvoidance](-cognitive-agent-obstacle-avoidance.md)

# CognitiveAgentObstacleAvoidance

[jvm]\
fun <[W](index.md) : [Obstacle2D](../../it.unibo.alchemist.model.interfaces/-obstacle2-d/index.md)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>, [T](index.md)> [CognitiveAgentObstacleAvoidance](-cognitive-agent-obstacle-avoidance.md)(env: [Environment2DWithObstacles](../../it.unibo.alchemist.model.interfaces.environments/-environment2-d-with-obstacles/index.md)<[W](index.md), [T](index.md)>, reaction: [SteeringBehavior](../../it.unibo.alchemist.model.implementations.reactions/-steering-behavior/index.md)<[T](index.md)>, pedestrian: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.md)<[T](index.md)>, proximityRange: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

## Parameters

jvm

| | |
|---|---|
| env | the environment inside which the pedestrian moves. |
| reaction | the reaction which executes this action. |
| pedestrian | the owner of this action. |
| proximityRange | the distance at which an obstacle is perceived by the pedestrian. |

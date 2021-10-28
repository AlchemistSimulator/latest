//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Incarnation](index.md)/[createReaction](create-reaction.md)

# createReaction

[jvm]\
abstract fun [createReaction](create-reaction.md)(randomGenerator: RandomGenerator, environment: [Environment](../-environment/index.md)<[T](../-action/index.md), [P](../../it.unibo.alchemist.core.interfaces/-simulation/index.md)>, node: [Node](../-node/index.md)<[T](../-action/index.md)>, timeDistribution: [TimeDistribution](../-time-distribution/index.md)<[T](../-action/index.md)>, parameter: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Reaction](../-reaction/index.md)<[T](../-action/index.md)>

#### Return

a new [Reaction](../-reaction/index.md)

## Parameters

jvm

| | |
|---|---|
| randomGenerator | the random engine |
| environment | the environment that will host this object |
| node | the node that will host this object |
| timeDistribution | the time distribution of the reaction |
| parameter | a [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) describing the object |
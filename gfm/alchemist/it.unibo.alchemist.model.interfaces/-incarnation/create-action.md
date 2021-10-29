//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Incarnation](index.md)/[createAction](create-action.md)

# createAction

[jvm]\
abstract fun [createAction](create-action.md)(randomGenerator: RandomGenerator, environment: [Environment](../-environment/index.md)<[T](../-node/index.md), [P](../../it.unibo.alchemist.core.interfaces/-simulation/index.md)>, node: [Node](../-node/index.md)<[T](../-node/index.md)>, time: [TimeDistribution](../-time-distribution/index.md)<[T](../-node/index.md)>, reaction: [Reaction](../-reaction/index.md)<[T](../-node/index.md)>, additionalParameters: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Action](../-action/index.md)<[T](../-node/index.md)>

#### Return

a new [Action](../-action/index.md)

## Parameters

jvm

| | |
|---|---|
| randomGenerator | the random engine |
| environment | the environment that will host this object |
| node | the node that will host this object |
| time | the time distribution of the reaction |
| reaction | the reaction hosting this object |
| additionalParameters | a [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) describing the object |

//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Incarnation](index.md)/[createCondition](create-condition.md)

# createCondition

[jvm]\
abstract fun [createCondition](create-condition.md)(randomGenerator: RandomGenerator, environment: [Environment](../-environment/index.md)<[T](../-action/index.md), [P](../-layer/index.md)>, node: [Node](../-node/index.md)<[T](../-action/index.md)>, time: [TimeDistribution](../-time-distribution/index.md)<[T](../-action/index.md)>, reaction: [Reaction](../-reaction/index.md)<[T](../-action/index.md)>, additionalParameters: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Condition](../-condition/index.md)<[T](../-action/index.md)>

#### Return

a new [Condition](../-condition/index.md)

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

//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Incarnation](index.md)/[createCondition](create-condition.md)

# createCondition

[jvm]\
abstract fun [createCondition](create-condition.md)(randomGenerator: RandomGenerator, environment: [Environment](../-environment/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md), [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)>, node: [Node](../-node/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)>, time: [TimeDistribution](../-time-distribution/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)>, reaction: [Reaction](../-reaction/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)>, additionalParameters: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Condition](../-condition/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)>

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

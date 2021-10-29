//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Incarnation](index.md)/[createTimeDistribution](create-time-distribution.md)

# createTimeDistribution

[jvm]\
abstract fun [createTimeDistribution](create-time-distribution.md)(randomGenerator: RandomGenerator, environment: [Environment](../-environment/index.md)<[T](../-node/index.md), [P](../../it.unibo.alchemist.core.interfaces/-simulation/index.md)>, node: [Node](../-node/index.md)<[T](../-node/index.md)>, @Nullable()parameter: @Nullable()[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [TimeDistribution](../-time-distribution/index.md)<[T](../-node/index.md)>

#### Return

a new [TimeDistribution](../-time-distribution/index.md)

## Parameters

jvm

| | |
|---|---|
| randomGenerator | the random engine |
| environment | the environment that will host this object |
| node | the node that will host this object |
| parameter | a [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) describing the object |

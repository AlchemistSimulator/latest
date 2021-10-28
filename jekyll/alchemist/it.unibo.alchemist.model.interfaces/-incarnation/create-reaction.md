---
title: createReaction
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Incarnation](index.html)/[createReaction](create-reaction.html)



# createReaction



[jvm]\
abstract fun [createReaction](create-reaction.html)(randomGenerator: RandomGenerator, environment: [Environment](../-environment/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, node: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, timeDistribution: [TimeDistribution](../-time-distribution/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, parameter: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Reaction](../-reaction/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>



#### Return



a new [Reaction](../-reaction/index.html)



## Parameters


jvm

| | |
|---|---|
| randomGenerator | the random engine |
| environment | the environment that will host this object |
| node | the node that will host this object |
| timeDistribution | the time distribution of the reaction |
| parameter | a [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) describing the object |





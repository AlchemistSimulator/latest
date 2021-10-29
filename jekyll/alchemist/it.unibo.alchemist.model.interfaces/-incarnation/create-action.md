---
title: createAction
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Incarnation](index.html)/[createAction](create-action.html)



# createAction



[jvm]\
abstract fun [createAction](create-action.html)(randomGenerator: RandomGenerator, environment: [Environment](../-environment/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, node: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, time: [TimeDistribution](../-time-distribution/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, reaction: [Reaction](../-reaction/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, additionalParameters: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Action](../-action/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>



#### Return



a new [Action](../-action/index.html)



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





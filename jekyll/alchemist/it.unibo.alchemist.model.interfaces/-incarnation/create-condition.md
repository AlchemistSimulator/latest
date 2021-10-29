---
title: createCondition
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Incarnation](index.html)/[createCondition](create-condition.html)



# createCondition



[jvm]\
abstract fun [createCondition](create-condition.html)(randomGenerator: RandomGenerator, environment: [Environment](../-environment/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, node: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, time: [TimeDistribution](../-time-distribution/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, reaction: [Reaction](../-reaction/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, additionalParameters: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Condition](../-condition/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>



#### Return



a new [Condition](../-condition/index.html)



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





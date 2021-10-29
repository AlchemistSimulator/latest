---
title: createAction
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Incarnation](index.html)/[createAction](create-action.html)



# createAction



[jvm]\
abstract fun [createAction](create-action.html)(randomGenerator: RandomGenerator, environment: [Environment](../-environment/index.html)<[T](../-node/index.html), [P](../-position2-d/index.html)>, node: [Node](../-node/index.html)<[T](../-node/index.html)>, time: [TimeDistribution](../-time-distribution/index.html)<[T](../-node/index.html)>, reaction: [Reaction](../-reaction/index.html)<[T](../-node/index.html)>, additionalParameters: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Action](../-action/index.html)<[T](../-node/index.html)>



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





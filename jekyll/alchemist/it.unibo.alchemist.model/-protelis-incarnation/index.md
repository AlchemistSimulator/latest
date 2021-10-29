---
title: ProtelisIncarnation
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model](../index.html)/[ProtelisIncarnation](index.html)



# ProtelisIncarnation



[jvm]\
class [ProtelisIncarnation](index.html)<[P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)>?> : [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)>



## Parameters


jvm

| | |
|---|---|
| <P> | position type |



## Types


| Name | Summary |
|---|---|
| [ProtectedExecutionEnvironment](-protected-execution-environment/index.html) | [jvm]<br>class [ProtectedExecutionEnvironment](-protected-execution-environment/index.html) : ExecutionEnvironment<br>An ExecutionEnvironment that can read and shadow the content of a [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html), but cannot modify it. |


## Functions


| Name | Summary |
|---|---|
| [createAction](create-action.html) | [jvm]<br>open fun [createAction](create-action.html)(randomGenerator: RandomGenerator, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, time: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, additionalParameters: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [createConcentration](create-concentration.html) | [jvm]<br>open fun [createConcentration](create-concentration.html)(s: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html) |
| [createCondition](create-condition.html) | [jvm]<br>open fun [createCondition](create-condition.html)(randomGenerator: RandomGenerator, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, time: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, additionalParameters: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [createMolecule](create-molecule.html) | [jvm]<br>open fun [createMolecule](create-molecule.html)(s: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html) |
| [createNode](create-node.html) | [jvm]<br>open fun [createNode](create-node.html)(randomGenerator: RandomGenerator, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)>, parameter: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [createReaction](create-reaction.html) | [jvm]<br>open fun [createReaction](create-reaction.html)(randomGenerator: RandomGenerator, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, timeDistribution: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, parameter: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [createTimeDistribution](create-time-distribution.html) | [jvm]<br>open fun [createTimeDistribution](create-time-distribution.html)(randomGenerator: RandomGenerator, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, parameter: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [getProperty](get-property.html) | [jvm]<br>open fun [getProperty](get-property.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), property: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Properties


| Name | Summary |
|---|---|
| [VALUE_TOKEN](-v-a-l-u-e_-t-o-k-e-n.html) | [jvm]<br>val [VALUE_TOKEN](-v-a-l-u-e_-t-o-k-e-n.html): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>The name that can be used in a property to refer to the extracted value. |


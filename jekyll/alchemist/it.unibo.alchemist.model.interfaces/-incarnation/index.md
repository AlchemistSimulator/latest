---
title: Incarnation
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Incarnation](index.html)



# Incarnation



[jvm]\
interface [Incarnation](index.html)<[T](index.html), [P](index.html) : [Position](../-position/index.html)<out [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>?>



## Parameters


jvm

| | |
|---|---|
| <T> | Concentration type |
| <P> | Concentration type |



## Functions


| Name | Summary |
|---|---|
| [createAction](create-action.html) | [jvm]<br>abstract fun [createAction](create-action.html)(randomGenerator: RandomGenerator, environment: [Environment](../-environment/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, node: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, time: [TimeDistribution](../-time-distribution/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, reaction: [Reaction](../-reaction/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, additionalParameters: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Action](../-action/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)><br>the random engine |
| [createConcentration](create-concentration.html) | [jvm]<br>abstract fun [createConcentration](create-concentration.html)(s: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)<br>Creates a new concentration object of a specific concrete type. |
| [createCondition](create-condition.html) | [jvm]<br>abstract fun [createCondition](create-condition.html)(randomGenerator: RandomGenerator, environment: [Environment](../-environment/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, node: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, time: [TimeDistribution](../-time-distribution/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, reaction: [Reaction](../-reaction/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, additionalParameters: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Condition](../-condition/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)><br>the random engine |
| [createMolecule](create-molecule.html) | [jvm]<br>abstract fun [createMolecule](create-molecule.html)(s: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Molecule](../-molecule/index.html)<br>Parses a [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), and provides a [Molecule](../-molecule/index.html). |
| [createNode](create-node.html) | [jvm]<br>abstract fun [createNode](create-node.html)(randomGenerator: RandomGenerator, environment: [Environment](../-environment/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, @Nullable()parameter: @Nullable()[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Node](../-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)><br>the random engine |
| [createReaction](create-reaction.html) | [jvm]<br>abstract fun [createReaction](create-reaction.html)(randomGenerator: RandomGenerator, environment: [Environment](../-environment/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, node: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, timeDistribution: [TimeDistribution](../-time-distribution/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, parameter: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Reaction](../-reaction/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)><br>the random engine |
| [createTimeDistribution](create-time-distribution.html) | [jvm]<br>abstract fun [createTimeDistribution](create-time-distribution.html)(randomGenerator: RandomGenerator, environment: [Environment](../-environment/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, node: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, @Nullable()parameter: @Nullable()[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [TimeDistribution](../-time-distribution/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)><br>the random engine |
| [getProperty](get-property.html) | [jvm]<br>abstract fun [getProperty](get-property.html)(node: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, molecule: [Molecule](../-molecule/index.html), property: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Given an [Node](../-node/index.html), an [Molecule](../-molecule/index.html) and a property expressed as a [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), returns a numeric value. |


## Inheritors


| Name |
|---|
| [BiochemistryIncarnation](../../it.unibo.alchemist.model/-biochemistry-incarnation/index.html) |
| [ProtelisIncarnation](../../it.unibo.alchemist.model/-protelis-incarnation/index.html) |
| [SAPEREIncarnation](../../it.unibo.alchemist.model/-s-a-p-e-r-e-incarnation/index.html) |


---
title: BiochemistryIncarnation
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model](../index.html)/[BiochemistryIncarnation](index.html)



# BiochemistryIncarnation



[jvm]\
class [BiochemistryIncarnation](index.html)<[P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>?, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>?> : [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>



## Parameters


jvm

| | |
|---|---|
| <P> | position type, must be a [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html) |



## Functions


| Name | Summary |
|---|---|
| [createAction](create-action.html) | [jvm]<br>open fun [createAction](create-action.html)(randomGenerator: RandomGenerator, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, time: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, additionalParameters: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> |
| [createConcentration](create-concentration.html) | [jvm]<br>open fun [createConcentration](create-concentration.html)(s: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html) |
| [createCondition](create-condition.html) | [jvm]<br>open fun [createCondition](create-condition.html)(randomGenerator: RandomGenerator, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, time: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, additionalParameters: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> |
| [createMolecule](create-molecule.html) | [jvm]<br>open fun [createMolecule](create-molecule.html)(s: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Biomolecule](../../it.unibo.alchemist.model.implementations.molecules/-biomolecule/index.html) |
| [createNode](create-node.html) | [jvm]<br>open fun [createNode](create-node.html)(randomGenerator: RandomGenerator, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>, parameter: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [CellNode](../../it.unibo.alchemist.model.interfaces/-cell-node/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)> |
| [createReaction](create-reaction.html) | [jvm]<br>open fun [createReaction](create-reaction.html)(randomGenerator: RandomGenerator, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, timeDistribution: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, parameter: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> |
| [createTimeDistribution](create-time-distribution.html) | [jvm]<br>open fun [createTimeDistribution](create-time-distribution.html)(randomGenerator: RandomGenerator, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, parameter: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> |
| [getProperty](get-property.html) | [jvm]<br>open fun [getProperty](get-property.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), property: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


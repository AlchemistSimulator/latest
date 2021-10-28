---
title: BiochemicalReactionBuilder
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.reactions](../index.html)/[BiochemicalReactionBuilder](index.html)



# BiochemicalReactionBuilder



[jvm]\
open class [BiochemicalReactionBuilder](index.html)<[P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>?, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>?>

This class implements a builder for chemical reactions.



## Parameters


jvm

| | |
|---|---|
| <P> | [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html) type |



## Constructors


| | |
|---|---|
| [BiochemicalReactionBuilder](-biochemical-reaction-builder.html) | [jvm]<br>open fun [BiochemicalReactionBuilder](-biochemical-reaction-builder.html)(inc: [BiochemistryIncarnation](../../it.unibo.alchemist.model/-biochemistry-incarnation/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>, currentNode: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>)<br>Construct a builder for biochemical reactions. |


## Functions


| Name | Summary |
|---|---|
| [build](build.html) | [jvm]<br>open fun [build](build.html)(): [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)><br>Builds the chemical reaction. |
| [program](program.html) | [jvm]<br>open fun [program](program.html)(program: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [BiochemicalReactionBuilder](index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)><br>Set the reaction to the passed program string. |
| [randomGenerator](random-generator.html) | [jvm]<br>open fun [randomGenerator](random-generator.html)(rg: RandomGenerator): [BiochemicalReactionBuilder](index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)><br>set the random generator to the passed object. |
| [timeDistribution](time-distribution.html) | [jvm]<br>open fun [timeDistribution](time-distribution.html)(td: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>): [BiochemicalReactionBuilder](index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)><br>Set the time distribution to the passed object. |


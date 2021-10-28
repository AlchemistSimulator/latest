//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.reactions](../index.md)/[BiochemicalReactionBuilder](index.md)

# BiochemicalReactionBuilder

[jvm]\
open class [BiochemicalReactionBuilder](index.md)<[P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>?, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](index.md)>?>

This class implements a builder for chemical reactions.

## Parameters

jvm

| | |
|---|---|
| <P> | [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md) type |

## Constructors

| | |
|---|---|
| [BiochemicalReactionBuilder](-biochemical-reaction-builder.md) | [jvm]<br>open fun [BiochemicalReactionBuilder](-biochemical-reaction-builder.md)(inc: [BiochemistryIncarnation](../../it.unibo.alchemist.model/-biochemistry-incarnation/index.md)<[P](index.md)>, currentNode: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), [P](index.md)>)<br>Construct a builder for biochemical reactions. |

## Functions

| Name | Summary |
|---|---|
| [build](build.md) | [jvm]<br>open fun [build](build.md)(): [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)><br>Builds the chemical reaction. |
| [program](program.md) | [jvm]<br>open fun [program](program.md)(program: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [BiochemicalReactionBuilder](index.md)<[P](index.md)><br>Set the reaction to the passed program string. |
| [randomGenerator](random-generator.md) | [jvm]<br>open fun [randomGenerator](random-generator.md)(rg: RandomGenerator): [BiochemicalReactionBuilder](index.md)<[P](index.md)><br>set the random generator to the passed object. |
| [timeDistribution](time-distribution.md) | [jvm]<br>open fun [timeDistribution](time-distribution.md)(td: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>): [BiochemicalReactionBuilder](index.md)<[P](index.md)><br>Set the time distribution to the passed object. |

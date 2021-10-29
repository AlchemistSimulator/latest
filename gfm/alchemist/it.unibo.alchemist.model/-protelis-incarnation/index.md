//[alchemist](../../../index.md)/[it.unibo.alchemist.model](../index.md)/[ProtelisIncarnation](index.md)

# ProtelisIncarnation

[jvm]\
class [ProtelisIncarnation](index.md)<[P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>?> : [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](index.md)>

## Parameters

jvm

| | |
|---|---|
| <P> | position type |

## Types

| Name | Summary |
|---|---|
| [ProtectedExecutionEnvironment](-protected-execution-environment/index.md) | [jvm]<br>class [ProtectedExecutionEnvironment](-protected-execution-environment/index.md) : ExecutionEnvironment<br>An ExecutionEnvironment that can read and shadow the content of a [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md), but cannot modify it. |

## Functions

| Name | Summary |
|---|---|
| [createAction](create-action.md) | [jvm]<br>open fun [createAction](create-action.md)(randomGenerator: RandomGenerator, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](index.md)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, time: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, additionalParameters: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [createConcentration](create-concentration.md) | [jvm]<br>open fun [createConcentration](create-concentration.md)(s: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html) |
| [createCondition](create-condition.md) | [jvm]<br>open fun [createCondition](create-condition.md)(randomGenerator: RandomGenerator, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](index.md)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, time: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, additionalParameters: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [createMolecule](create-molecule.md) | [jvm]<br>open fun [createMolecule](create-molecule.md)(s: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md) |
| [createNode](create-node.md) | [jvm]<br>open fun [createNode](create-node.md)(randomGenerator: RandomGenerator, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](index.md)>, parameter: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [createReaction](create-reaction.md) | [jvm]<br>open fun [createReaction](create-reaction.md)(randomGenerator: RandomGenerator, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](index.md)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, timeDistribution: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, parameter: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [createTimeDistribution](create-time-distribution.md) | [jvm]<br>open fun [createTimeDistribution](create-time-distribution.md)(randomGenerator: RandomGenerator, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](index.md)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, parameter: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [getProperty](get-property.md) | [jvm]<br>open fun [getProperty](get-property.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), property: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

## Properties

| Name | Summary |
|---|---|
| [VALUE_TOKEN](-v-a-l-u-e_-t-o-k-e-n.md) | [jvm]<br>val [VALUE_TOKEN](-v-a-l-u-e_-t-o-k-e-n.md): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>The name that can be used in a property to refer to the extracted value. |

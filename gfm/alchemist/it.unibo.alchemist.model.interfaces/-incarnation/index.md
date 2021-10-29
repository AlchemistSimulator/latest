//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Incarnation](index.md)

# Incarnation

[jvm]\
interface [Incarnation](index.md)<[T](index.md), [P](index.md) : [Position](../-position/index.md)<out [P](../-layer/index.md)>?>

## Parameters

jvm

| | |
|---|---|
| <T> | Concentration type |
| <P> | Concentration type |

## Functions

| Name | Summary |
|---|---|
| [createAction](create-action.md) | [jvm]<br>abstract fun [createAction](create-action.md)(randomGenerator: RandomGenerator, environment: [Environment](../-environment/index.md)<[T](../-action/index.md), [P](../-layer/index.md)>, node: [Node](../-node/index.md)<[T](../-action/index.md)>, time: [TimeDistribution](../-time-distribution/index.md)<[T](../-action/index.md)>, reaction: [Reaction](../-reaction/index.md)<[T](../-action/index.md)>, additionalParameters: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Action](../-action/index.md)<[T](../-action/index.md)><br>the random engine |
| [createConcentration](create-concentration.md) | [jvm]<br>abstract fun [createConcentration](create-concentration.md)(s: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [T](../-action/index.md)<br>Creates a new concentration object of a specific concrete type. |
| [createCondition](create-condition.md) | [jvm]<br>abstract fun [createCondition](create-condition.md)(randomGenerator: RandomGenerator, environment: [Environment](../-environment/index.md)<[T](../-action/index.md), [P](../-layer/index.md)>, node: [Node](../-node/index.md)<[T](../-action/index.md)>, time: [TimeDistribution](../-time-distribution/index.md)<[T](../-action/index.md)>, reaction: [Reaction](../-reaction/index.md)<[T](../-action/index.md)>, additionalParameters: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Condition](../-condition/index.md)<[T](../-action/index.md)><br>the random engine |
| [createMolecule](create-molecule.md) | [jvm]<br>abstract fun [createMolecule](create-molecule.md)(s: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Molecule](../-molecule/index.md)<br>Parses a [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), and provides a [Molecule](../-molecule/index.md). |
| [createNode](create-node.md) | [jvm]<br>abstract fun [createNode](create-node.md)(randomGenerator: RandomGenerator, environment: [Environment](../-environment/index.md)<[T](../-action/index.md), [P](../-layer/index.md)>, @Nullable()parameter: @Nullable()[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Node](../-node/index.md)<[T](../-action/index.md)><br>the random engine |
| [createReaction](create-reaction.md) | [jvm]<br>abstract fun [createReaction](create-reaction.md)(randomGenerator: RandomGenerator, environment: [Environment](../-environment/index.md)<[T](../-action/index.md), [P](../-layer/index.md)>, node: [Node](../-node/index.md)<[T](../-action/index.md)>, timeDistribution: [TimeDistribution](../-time-distribution/index.md)<[T](../-action/index.md)>, parameter: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Reaction](../-reaction/index.md)<[T](../-action/index.md)><br>the random engine |
| [createTimeDistribution](create-time-distribution.md) | [jvm]<br>abstract fun [createTimeDistribution](create-time-distribution.md)(randomGenerator: RandomGenerator, environment: [Environment](../-environment/index.md)<[T](../-action/index.md), [P](../-layer/index.md)>, node: [Node](../-node/index.md)<[T](../-action/index.md)>, @Nullable()parameter: @Nullable()[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [TimeDistribution](../-time-distribution/index.md)<[T](../-action/index.md)><br>the random engine |
| [getProperty](get-property.md) | [jvm]<br>abstract fun [getProperty](get-property.md)(node: [Node](../-node/index.md)<[T](../-action/index.md)>, molecule: [Molecule](../-molecule/index.md), property: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Given an [Node](../-node/index.md), an [Molecule](../-molecule/index.md) and a property expressed as a [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), returns a numeric value. |

## Inheritors

| Name |
|---|
| [BiochemistryIncarnation](../../it.unibo.alchemist.model/-biochemistry-incarnation/index.md) |
| [ProtelisIncarnation](../../it.unibo.alchemist.model/-protelis-incarnation/index.md) |
| [SAPEREIncarnation](../../it.unibo.alchemist.model/-s-a-p-e-r-e-incarnation/index.md) |

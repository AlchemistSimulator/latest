//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.timedistributions](../index.md)/[SAPEREExponentialTime](index.md)

# SAPEREExponentialTime

[jvm]\
class [SAPEREExponentialTime](index.md) : [ExponentialTime](../-exponential-time/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>> , [SAPERETimeDistribution](../-s-a-p-e-r-e-time-distribution/index.md)

Allows for a Markovian event whose lambda is computed dynamically using a rate equation.

## Constructors

| | |
|---|---|
| [SAPEREExponentialTime](-s-a-p-e-r-e-exponential-time.md) | [jvm]<br>open fun [SAPEREExponentialTime](-s-a-p-e-r-e-exponential-time.md)(rateEquation: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), random: RandomGenerator)<br>the rate equation |
| [SAPEREExponentialTime](-s-a-p-e-r-e-exponential-time.md) | [jvm]<br>open fun [SAPEREExponentialTime](-s-a-p-e-r-e-exponential-time.md)(rateEquation: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), start: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), random: RandomGenerator)<br>the rate equation |

## Functions

| Name | Summary |
|---|---|
| [cloneOnNewNode](../-abstract-distribution/clone-on-new-node.md) | [jvm]<br>abstract fun [cloneOnNewNode](../-abstract-distribution/clone-on-new-node.md)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)>, p1: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [AbstractDistribution](../-abstract-distribution/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)><br>open fun [cloneOnNewNode](../-exponential-time/clone-on-new-node.md)(destination: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)>, currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [ExponentialTime](../-exponential-time/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)><br>abstract fun [cloneOnNewNode](../../it.unibo.alchemist.model.interfaces/-time-distribution/clone-on-new-node.md)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)>, p1: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)> |
| [getNextOccurence](../-abstract-distribution/get-next-occurence.md) | [jvm]<br>fun [getNextOccurence](../-abstract-distribution/get-next-occurence.md)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md) |
| [getRate](get-rate.md) | [jvm]<br>open fun [getRate](get-rate.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getRateEquation](get-rate-equation.md) | [jvm]<br>open fun [getRateEquation](get-rate-equation.md)(): [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.md)<br>the rate equation |
| [isStatic](is-static.md) | [jvm]<br>open fun [isStatic](is-static.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if the equation is actually a number |
| [setMatches](../-s-a-p-e-r-e-time-distribution/set-matches.md) | [jvm]<br>abstract fun [setMatches](../-s-a-p-e-r-e-time-distribution/set-matches.md)(match: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>)<br>the map of matches |
| [update](../-abstract-distribution/update.md) | [jvm]<br>fun [update](../-abstract-distribution/update.md)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), hasBeenExecuted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), additionalParameter: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [updateStatus](../-exponential-time/update-status.md) | [jvm]<br>fun [updateStatus](../-exponential-time/update-status.md)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), executed: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), newpropensity: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |

## Properties

| Name | Summary |
|---|---|
| [matches](matches.md) | [jvm]<br>private open var [matches](matches.md): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>> |

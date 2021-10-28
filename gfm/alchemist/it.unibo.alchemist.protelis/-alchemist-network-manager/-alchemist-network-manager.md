//[alchemist](../../../index.md)/[it.unibo.alchemist.protelis](../index.md)/[AlchemistNetworkManager](index.md)/[AlchemistNetworkManager](-alchemist-network-manager.md)

# AlchemistNetworkManager

[jvm]\
open fun [AlchemistNetworkManager](-alchemist-network-manager.md)(executionTime: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, program: [RunProtelisProgram](../../it.unibo.alchemist.model.implementations.actions/-run-protelis-program/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)

## Parameters

jvm

| | |
|---|---|
| executionTime | the reaction hosting the NetworkManager |
| program | the [RunProtelisProgram](../../it.unibo.alchemist.model.implementations.actions/-run-protelis-program/index.md) |

[jvm]\
open fun [AlchemistNetworkManager](-alchemist-network-manager.md)(executionTime: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, program: [RunProtelisProgram](../../it.unibo.alchemist.model.implementations.actions/-run-protelis-program/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, retentionTime: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

## Parameters

jvm

| | |
|---|---|
| executionTime | the reaction hosting the NetworkManager |
| program | the [RunProtelisProgram](../../it.unibo.alchemist.model.implementations.actions/-run-protelis-program/index.md) |
| retentionTime | how long the messages will be stored. Pass [NaN](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html#NaN--) to mean that they should get eliminated upon node awake. |

[jvm]\
open fun [AlchemistNetworkManager](-alchemist-network-manager.md)(executionTime: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, program: [RunProtelisProgram](../../it.unibo.alchemist.model.implementations.actions/-run-protelis-program/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, retentionTime: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), distanceLossDistribution: RealDistribution)

## Parameters

jvm

| | |
|---|---|
| executionTime | the reaction hosting the NetworkManager |
| program | the [RunProtelisProgram](../../it.unibo.alchemist.model.implementations.actions/-run-protelis-program/index.md) |
| retentionTime | how long the messages will be stored. Pass [NaN](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html#NaN--) to mean that they should get eliminated upon node awake. |
| distanceLossDistribution | the package loss probability, scaling with distance. This RealDistribution will be used as follows: its PDF will be computed with density, and will be fed the distance between the current node and the neighbor; the generated probability will in turn be used to determine the probability of the package to be successfully delivered. Can be null, in which case packets always arrive to neighbors. |

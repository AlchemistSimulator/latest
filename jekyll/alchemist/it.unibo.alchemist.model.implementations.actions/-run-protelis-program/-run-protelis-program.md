---
title: RunProtelisProgram
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[RunProtelisProgram](index.html)/[RunProtelisProgram](-run-protelis-program.html)



# RunProtelisProgram



[jvm]\
open fun [RunProtelisProgram](-run-protelis-program.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)>, node: [ProtelisNode](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)<[P](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, randomGenerator: RandomGenerator, program: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))



## Parameters


jvm

| | |
|---|---|
| environment | the environment |
| node | the node |
| reaction | the reaction |
| randomGenerator | the random engine |
| program | the Protelis program |



#### Throws


| | |
|---|---|
| [java.lang.SecurityException](https://docs.oracle.com/javase/8/docs/api/java/lang/SecurityException.html) | if you are not authorized to load required classes |




[jvm]\
open fun [RunProtelisProgram](-run-protelis-program.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)>, node: [ProtelisNode](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)<[P](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, randomGenerator: RandomGenerator, program: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), retentionTime: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))



## Parameters


jvm

| | |
|---|---|
| environment | the environment |
| node | the node |
| reaction | the reaction |
| randomGenerator | the random engine |
| program | the Protelis program |
| retentionTime | how long the messages will be stored. Pass [NaN](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html#NaN--) to mean that they should get eliminated upon node awake. |



#### Throws


| | |
|---|---|
| [java.lang.SecurityException](https://docs.oracle.com/javase/8/docs/api/java/lang/SecurityException.html) | if you are not authorized to load required classes |




[jvm]\
open fun [RunProtelisProgram](-run-protelis-program.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)>, node: [ProtelisNode](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)<[P](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, randomGenerator: RandomGenerator, program: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), packetLossDistributionName: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), packetLossDistributionParameters: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>)



## Parameters


jvm

| | |
|---|---|
| environment | the environment |
| node | the node |
| reaction | the reaction |
| randomGenerator | the random engine |
| program | the Protelis program |
| packetLossDistributionName | the package loss probability, scaling with distance. This is the name of the RealDistribution to be used as follows: its PDF will be computed with density, and will be fed the distance between the current node and the neighbor; the generated probability will in turn be used to determine the probability of the package to be successfully delivered. |
| packetLossDistributionParameters | parameters that will be passed when building the packet loss distribution |



#### Throws


| | |
|---|---|
| [java.lang.SecurityException](https://docs.oracle.com/javase/8/docs/api/java/lang/SecurityException.html) | if you are not authorized to load required classes |




[jvm]\
open fun [RunProtelisProgram](-run-protelis-program.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)>, node: [ProtelisNode](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)<[P](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, randomGenerator: RandomGenerator, program: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), retentionTime: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), packetLossDistributionName: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), packetLossDistributionParameters: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>)

open fun [RunProtelisProgram](-run-protelis-program.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)>, node: [ProtelisNode](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)<[P](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, randomGenerator: RandomGenerator, program: ProtelisProgram, retentionTime: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), packetLossDistributionName: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), packetLossDistributionParameters: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>)



## Parameters


jvm

| | |
|---|---|
| environment | the environment |
| node | the node |
| reaction | the reaction |
| randomGenerator | the random engine |
| program | the Protelis program |
| retentionTime | how long the messages will be stored. Pass [NaN](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html#NaN--) to mean that they should get eliminated upon node awake. |
| packetLossDistributionName | the package loss probability, scaling with distance. This is the name of the RealDistribution to be used as follows: its PDF will be computed with density, and will be fed the distance between the current node and the neighbor; the generated probability will in turn be used to determine the probability of the package to be successfully delivered. |
| packetLossDistributionParameters | parameters that will be passed when building the packet loss distribution |



#### Throws


| | |
|---|---|
| [java.lang.SecurityException](https://docs.oracle.com/javase/8/docs/api/java/lang/SecurityException.html) | if you are not authorized to load required classes |




[jvm]\
open fun [RunProtelisProgram](-run-protelis-program.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)>, node: [ProtelisNode](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)<[P](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, randomGenerator: RandomGenerator, program: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), retentionTime: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), packetLossDistance: RealDistribution)



## Parameters


jvm

| | |
|---|---|
| environment | the environment |
| node | the node |
| reaction | the reaction |
| randomGenerator | the random engine |
| program | the Protelis program |
| retentionTime | how long the messages will be stored. Pass [NaN](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html#NaN--) to mean that they should get eliminated upon node awake. |
| packetLossDistance | the package loss probability, scaling with distance. This RealDistribution will be used as follows: its PDF will be computed with density, and will be fed the distance between the current node and the neighbor; the generated probability will in turn be used to determine the probability of the package to be successfully delivered. Can be null, in which case packets always arrive to neighbors. |



#### Throws


| | |
|---|---|
| [java.lang.SecurityException](https://docs.oracle.com/javase/8/docs/api/java/lang/SecurityException.html) | if you are not authorized to load required classes |




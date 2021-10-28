---
title: RunProtelisProgram
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[RunProtelisProgram](index.html)



# RunProtelisProgram



[jvm]\
class [RunProtelisProgram](index.html)<[P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../../it.unibo.alchemist.model/-protelis-incarnation/index.html)>?> : [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>



## Parameters


jvm

| | |
|---|---|
| <P> | position type |



## Constructors


| | |
|---|---|
| [RunProtelisProgram](-run-protelis-program.html) | [jvm]<br>open fun [RunProtelisProgram](-run-protelis-program.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.model/-protelis-incarnation/index.html)>, node: [ProtelisNode](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)<[P](../../it.unibo.alchemist.model/-protelis-incarnation/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, randomGenerator: RandomGenerator, program: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>the environment |
| [RunProtelisProgram](-run-protelis-program.html) | [jvm]<br>open fun [RunProtelisProgram](-run-protelis-program.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.model/-protelis-incarnation/index.html)>, node: [ProtelisNode](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)<[P](../../it.unibo.alchemist.model/-protelis-incarnation/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, randomGenerator: RandomGenerator, program: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), retentionTime: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>the environment |
| [RunProtelisProgram](-run-protelis-program.html) | [jvm]<br>open fun [RunProtelisProgram](-run-protelis-program.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.model/-protelis-incarnation/index.html)>, node: [ProtelisNode](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)<[P](../../it.unibo.alchemist.model/-protelis-incarnation/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, randomGenerator: RandomGenerator, program: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), packetLossDistributionName: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), packetLossDistributionParameters: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>)<br>the environment |
| [RunProtelisProgram](-run-protelis-program.html) | [jvm]<br>open fun [RunProtelisProgram](-run-protelis-program.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.model/-protelis-incarnation/index.html)>, node: [ProtelisNode](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)<[P](../../it.unibo.alchemist.model/-protelis-incarnation/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, randomGenerator: RandomGenerator, program: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), retentionTime: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), packetLossDistributionName: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), packetLossDistributionParameters: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>)<br>the environment |
| [RunProtelisProgram](-run-protelis-program.html) | [jvm]<br>open fun [RunProtelisProgram](-run-protelis-program.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.model/-protelis-incarnation/index.html)>, node: [ProtelisNode](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)<[P](../../it.unibo.alchemist.model/-protelis-incarnation/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, randomGenerator: RandomGenerator, program: ProtelisProgram, retentionTime: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), packetLossDistributionName: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), packetLossDistributionParameters: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>)<br>the environment |
| [RunProtelisProgram](-run-protelis-program.html) | [jvm]<br>open fun [RunProtelisProgram](-run-protelis-program.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.model/-protelis-incarnation/index.html)>, node: [ProtelisNode](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)<[P](../../it.unibo.alchemist.model/-protelis-incarnation/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, randomGenerator: RandomGenerator, program: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), retentionTime: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), packetLossDistance: RealDistribution)<br>the environment |


## Functions


| Name | Summary |
|---|---|
| [asMolecule](as-molecule.html) | [jvm]<br>open fun [asMolecule](as-molecule.html)(): [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)<br>the molecule associated with the execution of this program |
| [cloneAction](clone-action.html) | [jvm]<br>open fun [cloneAction](clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [RunProtelisProgram](index.html)<[P](../../it.unibo.alchemist.model/-protelis-incarnation/index.html)> |
| [equals](equals.html) | [jvm]<br>open fun [equals](equals.html)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [execute](execute.html) | [jvm]<br>open fun [execute](execute.html)() |
| [getContext](get-context.html) | [jvm]<br>open fun [getContext](get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getOutboundDependencies](get-outbound-dependencies.html) | [jvm]<br>open fun [getOutboundDependencies](get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [getRandomGenerator](get-random-generator.html) | [jvm]<br>open fun [getRandomGenerator](get-random-generator.html)(): RandomGenerator<br>the internal RandomGenerator |
| [hashCode](hash-code.html) | [jvm]<br>open fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isComputationalCycleComplete](is-computational-cycle-complete.html) | [jvm]<br>open fun [isComputationalCycleComplete](is-computational-cycle-complete.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if the Program has finished its last computation, and is ready to send a new message (used for dependency management) |
| [prepareForComputationalCycle](prepare-for-computational-cycle.html) | [jvm]<br>open fun [prepareForComputationalCycle](prepare-for-computational-cycle.html)()<br>Resets the computation status (used for dependency management). |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Properties


| Name | Summary |
|---|---|
| [environment](environment.html) | [jvm]<br>private val [environment](environment.html): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.model/-protelis-incarnation/index.html)> |
| [executionContext](execution-context.html) | [jvm]<br>private open val [executionContext](execution-context.html): [AlchemistExecutionContext](../../it.unibo.alchemist.protelis/-alchemist-execution-context/index.html)<[P](../../it.unibo.alchemist.model/-protelis-incarnation/index.html)> |
| [node](node.html) | [jvm]<br>private val [node](node.html): [ProtelisNode](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)<[P](../../it.unibo.alchemist.model/-protelis-incarnation/index.html)> |
| [retentionTime](retention-time.html) | [jvm]<br>private val [retentionTime](retention-time.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |


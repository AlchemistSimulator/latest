---
title: ComputationalRoundComplete
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.conditions](../index.html)/[ComputationalRoundComplete](index.html)



# ComputationalRoundComplete



[jvm]\
class [ComputationalRoundComplete](index.html) : [AbstractCondition](../-abstract-condition/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>



## Constructors


| | |
|---|---|
| [ComputationalRoundComplete](-computational-round-complete.html) | [jvm]<br>open fun [ComputationalRoundComplete](-computational-round-complete.html)(node: [ProtelisNode](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, program: [RunProtelisProgram](../../it.unibo.alchemist.model.implementations.actions/-run-protelis-program/index.html))<br>the local node |


## Functions


| Name | Summary |
|---|---|
| [cloneCondition](clone-condition.html) | [jvm]<br>open fun [cloneCondition](clone-condition.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [ComputationalRoundComplete](index.html) |
| [getContext](get-context.html) | [jvm]<br>open fun [getContext](get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.html) | [jvm]<br>fun [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [getNode](get-node.html) | [jvm]<br>open fun [getNode](get-node.html)(): [ProtelisNode](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [getPropensityContribution](get-propensity-contribution.html) | [jvm]<br>open fun [getPropensityContribution](get-propensity-contribution.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [isValid](is-valid.html) | [jvm]<br>open fun [isValid](is-valid.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.html) | [jvm]<br>open fun [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.html)() |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


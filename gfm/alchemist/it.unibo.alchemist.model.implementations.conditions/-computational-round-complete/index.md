//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.conditions](../index.md)/[ComputationalRoundComplete](index.md)

# ComputationalRoundComplete

[jvm]\
class [ComputationalRoundComplete](index.md) : [AbstractCondition](../-abstract-condition/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>

## Constructors

| | |
|---|---|
| [ComputationalRoundComplete](-computational-round-complete.md) | [jvm]<br>open fun [ComputationalRoundComplete](-computational-round-complete.md)(node: [ProtelisNode](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, program: [RunProtelisProgram](../../it.unibo.alchemist.model.implementations.actions/-run-protelis-program/index.md))<br>the local node |

## Functions

| Name | Summary |
|---|---|
| [cloneCondition](clone-condition.md) | [jvm]<br>open fun [cloneCondition](clone-condition.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [ComputationalRoundComplete](index.md) |
| [getContext](get-context.md) | [jvm]<br>open fun [getContext](get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.md) | [jvm]<br>fun [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [getNode](get-node.md) | [jvm]<br>open fun [getNode](get-node.md)(): [ProtelisNode](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [getPropensityContribution](get-propensity-contribution.md) | [jvm]<br>open fun [getPropensityContribution](get-propensity-contribution.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [isValid](is-valid.md) | [jvm]<br>open fun [isValid](is-valid.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.md) | [jvm]<br>open fun [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.md)() |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

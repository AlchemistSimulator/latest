---
title: SAPEREGradient
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.reactions](../index.html)/[SAPEREGradient](index.html)



# SAPEREGradient



[jvm]\
class [SAPEREGradient](index.html)<[P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../../it.unibo.alchemist.model.implementations.actions/-lsa-ascending-gradient-dist/index.html)>?> : [AbstractReaction](../-abstract-reaction/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>> 

This class provides a fast and stable gradient implementation, inspired on the NBR construct used in Proto.



## Parameters


jvm

| | |
|---|---|
| <P> | Position type |



## Constructors


| | |
|---|---|
| [SAPEREGradient](-s-a-p-e-r-e-gradient.html) | [jvm]<br>open fun [SAPEREGradient](-s-a-p-e-r-e-gradient.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>, [P](../../it.unibo.alchemist.model.implementations.actions/-lsa-ascending-gradient-dist/index.html)>, node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html), sourceTemplate: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html), gradientTemplate: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html), valuePosition: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), expression: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), contextTemplate: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html), gradThreshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), timeDistribution: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>)<br>Builds a new SAPERE Gradient. |
| [SAPEREGradient](-s-a-p-e-r-e-gradient.html) | [jvm]<br>open fun [SAPEREGradient](-s-a-p-e-r-e-gradient.html)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>, [P](../../it.unibo.alchemist.model.implementations.actions/-lsa-ascending-gradient-dist/index.html)>, n: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html), td: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>, sourceTemplate: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), gradientTemplate: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), valuePosition: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), expression: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), contextTemplate: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), gradThreshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Builds a new SAPERE Gradient. |


## Functions


| Name | Summary |
|---|---|
| [canExecute](can-execute.html) | [jvm]<br>open fun [canExecute](can-execute.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [cloneOnNewNode](clone-on-new-node.html) | [jvm]<br>open fun [cloneOnNewNode](clone-on-new-node.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>, currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>> |
| [compareTo](../-abstract-reaction/compare-to.html) | [jvm]<br>fun [compareTo](../-abstract-reaction/compare-to.html)(o: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [equals](../-abstract-reaction/equals.html) | [jvm]<br>fun [equals](../-abstract-reaction/equals.html)(o: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [execute](execute.html) | [jvm]<br>open fun [execute](execute.html)() |
| [getActions](get-actions.html) | [jvm]<br>open fun [getActions](get-actions.html)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>> |
| [getConditions](get-conditions.html) | [jvm]<br>open fun [getConditions](get-conditions.html)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>>> |
| [getInboundDependencies](../-abstract-reaction/get-inbound-dependencies.html) | [jvm]<br>fun [getInboundDependencies](../-abstract-reaction/get-inbound-dependencies.html)(): ListSet<[Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)><br>abstract fun [getInboundDependencies](../../it.unibo.alchemist.model.interfaces/-reaction/get-inbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [getInputContext](../-abstract-reaction/get-input-context.html) | [jvm]<br>fun [getInputContext](../-abstract-reaction/get-input-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getLsaNode](get-lsa-node.html) | [jvm]<br>open fun [getLsaNode](get-lsa-node.html)(): [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html)<br>the current node as [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html) |
| [getNode](../-navigation-prioritised-steering-with-physics/index.html#-1244046302%2FFunctions%2F-134779887) | [jvm]<br>fun [getNode](../-navigation-prioritised-steering-with-physics/index.html#-1244046302%2FFunctions%2F-134779887)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.html)> |
| [getOutboundDependencies](../-abstract-reaction/get-outbound-dependencies.html) | [jvm]<br>fun [getOutboundDependencies](../-abstract-reaction/get-outbound-dependencies.html)(): ListSet<[Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)><br>abstract fun [getOutboundDependencies](../../it.unibo.alchemist.model.interfaces/-reaction/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [getOutputContext](../-abstract-reaction/get-output-context.html) | [jvm]<br>fun [getOutputContext](../-abstract-reaction/get-output-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getRate](get-rate.html) | [jvm]<br>open fun [getRate](get-rate.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getTau](../-abstract-reaction/get-tau.html) | [jvm]<br>fun [getTau](../-abstract-reaction/get-tau.html)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html) |
| [getTimeDistribution](../-navigation-prioritised-steering-with-physics/index.html#2053953683%2FFunctions%2F-134779887) | [jvm]<br>fun [getTimeDistribution](../-navigation-prioritised-steering-with-physics/index.html#2053953683%2FFunctions%2F-134779887)(): [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.html)> |
| [hashCode](../-abstract-reaction/hash-code.html) | [jvm]<br>fun [hashCode](../-abstract-reaction/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [initializationComplete](../-abstract-reaction/initialization-complete.html) | [jvm]<br>open fun [initializationComplete](../-abstract-reaction/initialization-complete.html)(atTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [setActions](index.html#2022331282%2FFunctions%2F-134779887) | [jvm]<br>open fun [setActions](index.html#2022331282%2FFunctions%2F-134779887)(actions: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.html)>>) |
| [setConditions](index.html#1708622090%2FFunctions%2F-134779887) | [jvm]<br>open fun [setConditions](index.html#1708622090%2FFunctions%2F-134779887)(conditions: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.html)>>) |
| [toString](../-abstract-reaction/to-string.html) | [jvm]<br>open fun [toString](../-abstract-reaction/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [update](../-abstract-reaction/update.html) | [jvm]<br>fun [update](../-abstract-reaction/update.html)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), hasBeenExecuted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |


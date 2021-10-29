---
title: BiochemicalReaction
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.reactions](../index.html)/[BiochemicalReaction](index.html)



# BiochemicalReaction



[jvm]\
class [BiochemicalReaction](index.html) : [ChemicalReaction](../-chemical-reaction/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> 

A biochemical Reaction.



## Constructors


| | |
|---|---|
| [BiochemicalReaction](-biochemical-reaction.html) | [jvm]<br>open fun [BiochemicalReaction](-biochemical-reaction.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, timeDistribution: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, randomGenerator: RandomGenerator)<br>node |


## Functions


| Name | Summary |
|---|---|
| [canExecute](../-abstract-reaction/can-execute.html) | [jvm]<br>open fun [canExecute](../-abstract-reaction/can-execute.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [cloneOnNewNode](clone-on-new-node.html) | [jvm]<br>open fun [cloneOnNewNode](clone-on-new-node.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [BiochemicalReaction](index.html)<br>abstract fun [cloneOnNewNode](../../it.unibo.alchemist.model.interfaces/-reaction/clone-on-new-node.html)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.html)>, p1: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.html)> |
| [compareTo](../-abstract-reaction/compare-to.html) | [jvm]<br>fun [compareTo](../-abstract-reaction/compare-to.html)(o: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [equals](../-abstract-reaction/equals.html) | [jvm]<br>fun [equals](../-abstract-reaction/equals.html)(o: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [execute](execute.html) | [jvm]<br>open fun [execute](execute.html)() |
| [getActions](../-navigation-prioritised-steering-with-physics/index.html#13515737%2FFunctions%2F-134779887) | [jvm]<br>open fun [getActions](../-navigation-prioritised-steering-with-physics/index.html#13515737%2FFunctions%2F-134779887)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.html)>> |
| [getConditions](../-navigation-prioritised-steering-with-physics/index.html#-184159508%2FFunctions%2F-134779887) | [jvm]<br>open fun [getConditions](../-navigation-prioritised-steering-with-physics/index.html#-184159508%2FFunctions%2F-134779887)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.html)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.html)>> |
| [getInboundDependencies](../-abstract-reaction/get-inbound-dependencies.html) | [jvm]<br>fun [getInboundDependencies](../-abstract-reaction/get-inbound-dependencies.html)(): ListSet<[Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)><br>abstract fun [getInboundDependencies](../../it.unibo.alchemist.model.interfaces/-reaction/get-inbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [getInputContext](../-abstract-reaction/get-input-context.html) | [jvm]<br>fun [getInputContext](../-abstract-reaction/get-input-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getNode](../-navigation-prioritised-steering-with-physics/index.html#-1244046302%2FFunctions%2F-134779887) | [jvm]<br>fun [getNode](../-navigation-prioritised-steering-with-physics/index.html#-1244046302%2FFunctions%2F-134779887)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.html)> |
| [getOutboundDependencies](../-abstract-reaction/get-outbound-dependencies.html) | [jvm]<br>fun [getOutboundDependencies](../-abstract-reaction/get-outbound-dependencies.html)(): ListSet<[Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)><br>abstract fun [getOutboundDependencies](../../it.unibo.alchemist.model.interfaces/-reaction/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [getOutputContext](../-abstract-reaction/get-output-context.html) | [jvm]<br>fun [getOutputContext](../-abstract-reaction/get-output-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getRate](../-chemical-reaction/get-rate.html) | [jvm]<br>fun [getRate](../-chemical-reaction/get-rate.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getTau](../-abstract-reaction/get-tau.html) | [jvm]<br>fun [getTau](../-abstract-reaction/get-tau.html)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html) |
| [getTimeDistribution](../-navigation-prioritised-steering-with-physics/index.html#2053953683%2FFunctions%2F-134779887) | [jvm]<br>fun [getTimeDistribution](../-navigation-prioritised-steering-with-physics/index.html#2053953683%2FFunctions%2F-134779887)(): [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.html)> |
| [hashCode](../-abstract-reaction/hash-code.html) | [jvm]<br>fun [hashCode](../-abstract-reaction/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [initializationComplete](../-chemical-reaction/initialization-complete.html) | [jvm]<br>fun [initializationComplete](../-chemical-reaction/initialization-complete.html)(atTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [setActions](../-s-a-p-e-r-e-gradient/index.html#2022331282%2FFunctions%2F-134779887) | [jvm]<br>open fun [setActions](../-s-a-p-e-r-e-gradient/index.html#2022331282%2FFunctions%2F-134779887)(actions: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.html)>>) |
| [setConditions](set-conditions.html) | [jvm]<br>open fun [setConditions](set-conditions.html)(conditions: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>>) |
| [toString](../-abstract-reaction/to-string.html) | [jvm]<br>open fun [toString](../-abstract-reaction/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [update](../-abstract-reaction/update.html) | [jvm]<br>fun [update](../-abstract-reaction/update.html)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), hasBeenExecuted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |


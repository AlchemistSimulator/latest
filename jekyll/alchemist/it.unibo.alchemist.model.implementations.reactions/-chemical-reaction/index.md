---
title: ChemicalReaction
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.reactions](../index.html)/[ChemicalReaction](index.html)



# ChemicalReaction



[jvm]\
open class [ChemicalReaction](index.html)<[T](index.html)> : [AbstractReaction](../-abstract-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Constructors


| | |
|---|---|
| [ChemicalReaction](-chemical-reaction.html) | [jvm]<br>open fun [ChemicalReaction](-chemical-reaction.html)(n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>, pd: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>)<br>node |


## Functions


| Name | Summary |
|---|---|
| [canExecute](../-abstract-reaction/can-execute.html) | [jvm]<br>open fun [canExecute](../-abstract-reaction/can-execute.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>The default implementation verifies if all the conditions are valid.<br>[jvm]<br>abstract fun [canExecute](../../it.unibo.alchemist.model.interfaces/-reaction/can-execute.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [cloneOnNewNode](clone-on-new-node.html) | [jvm]<br>open fun [cloneOnNewNode](clone-on-new-node.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>, currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [ChemicalReaction](index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)> |
| [compareTo](../-abstract-reaction/compare-to.html) | [jvm]<br>fun [compareTo](../-abstract-reaction/compare-to.html)(o: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>abstract fun [compareTo](../../it.unibo.alchemist.model.interfaces/-g-p-s-point/index.html#-1554281679%2FFunctions%2F-134779887)(p: [T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [equals](../-abstract-reaction/equals.html) | [jvm]<br>fun [equals](../-abstract-reaction/equals.html)(o: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [execute](../-abstract-reaction/execute.html) | [jvm]<br>open fun [execute](../-abstract-reaction/execute.html)()<br>The default execution iterates all the actions in order and executes them.<br>[jvm]<br>abstract fun [execute](../../it.unibo.alchemist.model.interfaces/-reaction/execute.html)() |
| [getActions](../-navigation-prioritised-steering-with-physics/index.html#13515737%2FFunctions%2F-134779887) | [jvm]<br>open fun [getActions](../-navigation-prioritised-steering-with-physics/index.html#13515737%2FFunctions%2F-134779887)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>><br>Override only if you need to implement extremely tricky behaviours.<br>[jvm]<br>abstract fun [getActions](../../it.unibo.alchemist.model.interfaces/-reaction/get-actions.html)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>> |
| [getConditions](../-navigation-prioritised-steering-with-physics/index.html#-184159508%2FFunctions%2F-134779887) | [jvm]<br>open fun [getConditions](../-navigation-prioritised-steering-with-physics/index.html#-184159508%2FFunctions%2F-134779887)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>><br>Override only if you need to implement extremely tricky behaviours.<br>[jvm]<br>abstract fun [getConditions](../../it.unibo.alchemist.model.interfaces/-reaction/get-conditions.html)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>> |
| [getInboundDependencies](../-abstract-reaction/get-inbound-dependencies.html) | [jvm]<br>fun [getInboundDependencies](../-abstract-reaction/get-inbound-dependencies.html)(): ListSet<[Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)><br>abstract fun [getInboundDependencies](../../it.unibo.alchemist.model.interfaces/-reaction/get-inbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [getInputContext](../-abstract-reaction/get-input-context.html) | [jvm]<br>fun [getInputContext](../-abstract-reaction/get-input-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html)<br>abstract fun [getInputContext](../../it.unibo.alchemist.model.interfaces/-reaction/get-input-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getNode](../-navigation-prioritised-steering-with-physics/index.html#-1244046302%2FFunctions%2F-134779887) | [jvm]<br>fun [getNode](../-navigation-prioritised-steering-with-physics/index.html#-1244046302%2FFunctions%2F-134779887)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)><br>abstract fun [getNode](../../it.unibo.alchemist.model.interfaces/-reaction/get-node.html)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)> |
| [getOutboundDependencies](../-abstract-reaction/get-outbound-dependencies.html) | [jvm]<br>fun [getOutboundDependencies](../-abstract-reaction/get-outbound-dependencies.html)(): ListSet<[Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)><br>abstract fun [getOutboundDependencies](../../it.unibo.alchemist.model.interfaces/-reaction/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [getOutputContext](../-abstract-reaction/get-output-context.html) | [jvm]<br>fun [getOutputContext](../-abstract-reaction/get-output-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html)<br>abstract fun [getOutputContext](../../it.unibo.alchemist.model.interfaces/-reaction/get-output-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getRate](get-rate.html) | [jvm]<br>fun [getRate](get-rate.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getTau](../-abstract-reaction/get-tau.html) | [jvm]<br>fun [getTau](../-abstract-reaction/get-tau.html)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)<br>abstract fun [getTau](../../it.unibo.alchemist.model.interfaces/-reaction/get-tau.html)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html) |
| [getTimeDistribution](../-navigation-prioritised-steering-with-physics/index.html#2053953683%2FFunctions%2F-134779887) | [jvm]<br>fun [getTimeDistribution](../-navigation-prioritised-steering-with-physics/index.html#2053953683%2FFunctions%2F-134779887)(): [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)><br>abstract fun [getTimeDistribution](../../it.unibo.alchemist.model.interfaces/-reaction/get-time-distribution.html)(): [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)> |
| [hashCode](../-abstract-reaction/hash-code.html) | [jvm]<br>fun [hashCode](../-abstract-reaction/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [initializationComplete](initialization-complete.html) | [jvm]<br>fun [initializationComplete](initialization-complete.html)(atTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>abstract fun [initializationComplete](../../it.unibo.alchemist.model.interfaces/-reaction/initialization-complete.html)(p: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), p1: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [setActions](../-s-a-p-e-r-e-gradient/index.html#2022331282%2FFunctions%2F-134779887) | [jvm]<br>open fun [setActions](../-s-a-p-e-r-e-gradient/index.html#2022331282%2FFunctions%2F-134779887)(actions: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>>)<br>This should get overridden only if very tricky behaviours are implemented, such that the default Alchemist action addition model is no longer usable.<br>[jvm]<br>abstract fun [setActions](../../it.unibo.alchemist.model.interfaces/-reaction/set-actions.html)(p: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>>) |
| [setConditions](../-s-a-p-e-r-e-gradient/index.html#1708622090%2FFunctions%2F-134779887) | [jvm]<br>open fun [setConditions](../-s-a-p-e-r-e-gradient/index.html#1708622090%2FFunctions%2F-134779887)(conditions: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>>)<br>This should get overridden only if very tricky behaviours are implemented, such that the default Alchemist condition addition model is no longer usable.<br>[jvm]<br>abstract fun [setConditions](../../it.unibo.alchemist.model.interfaces/-reaction/set-conditions.html)(p: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>>) |
| [toString](../-abstract-reaction/to-string.html) | [jvm]<br>open fun [toString](../-abstract-reaction/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>the default implementation returns a String in the form className@timeScheduled[Conditions]-rate->[Actions] |
| [update](../-abstract-reaction/update.html) | [jvm]<br>fun [update](../-abstract-reaction/update.html)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), hasBeenExecuted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>abstract fun [update](../../it.unibo.alchemist.model.interfaces/-reaction/update.html)(p: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), p1: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), p2: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |


## Inheritors


| Name |
|---|
| [BiochemicalReaction](../-biochemical-reaction/index.html) |


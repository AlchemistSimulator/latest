//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.reactions](../index.md)/[Event](index.md)

# Event

[jvm]\
class [Event](index.md)<[T](index.md)> : [AbstractReaction](../-abstract-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)> 

This reaction completely ignores the propensity conditioning of the conditions, and tries to run every time the [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.md) wants to.

## Parameters

jvm

| | |
|---|---|
| <T> | concentration type |

## Constructors

| | |
|---|---|
| [Event](-event.md) | [jvm]<br>open fun [Event](-event.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>, timedist: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>)<br>the node this [Event](index.md) belongs to |

## Functions

| Name | Summary |
|---|---|
| [canExecute](../-abstract-reaction/can-execute.md) | [jvm]<br>open fun [canExecute](../-abstract-reaction/can-execute.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>The default implementation verifies if all the conditions are valid.<br>[jvm]<br>abstract fun [canExecute](../../it.unibo.alchemist.model.interfaces/-reaction/can-execute.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [cloneOnNewNode](clone-on-new-node.md) | [jvm]<br>open fun [cloneOnNewNode](clone-on-new-node.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>, currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [Event](index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)> |
| [compareTo](../-abstract-reaction/compare-to.md) | [jvm]<br>fun [compareTo](../-abstract-reaction/compare-to.md)(o: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>abstract fun [compareTo](../../it.unibo.alchemist.model.interfaces/-g-p-s-point/index.md#-1554281679%2FFunctions%2F-267951372)(p: [T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [equals](../-abstract-reaction/equals.md) | [jvm]<br>fun [equals](../-abstract-reaction/equals.md)(o: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [execute](../-abstract-reaction/execute.md) | [jvm]<br>open fun [execute](../-abstract-reaction/execute.md)()<br>The default execution iterates all the actions in order and executes them.<br>[jvm]<br>abstract fun [execute](../../it.unibo.alchemist.model.interfaces/-reaction/execute.md)() |
| [getActions](../-navigation-prioritised-steering-with-physics/index.md#13515737%2FFunctions%2F-267951372) | [jvm]<br>open fun [getActions](../-navigation-prioritised-steering-with-physics/index.md#13515737%2FFunctions%2F-267951372)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Action](../../it.unibo.alchemist.model.interfaces/-action/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>><br>Override only if you need to implement extremely tricky behaviours.<br>[jvm]<br>abstract fun [getActions](../../it.unibo.alchemist.model.interfaces/-reaction/get-actions.md)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Action](../../it.unibo.alchemist.model.interfaces/-action/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>> |
| [getConditions](../-navigation-prioritised-steering-with-physics/index.md#-184159508%2FFunctions%2F-267951372) | [jvm]<br>open fun [getConditions](../-navigation-prioritised-steering-with-physics/index.md#-184159508%2FFunctions%2F-267951372)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>><br>Override only if you need to implement extremely tricky behaviours.<br>[jvm]<br>abstract fun [getConditions](../../it.unibo.alchemist.model.interfaces/-reaction/get-conditions.md)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>> |
| [getInboundDependencies](../-abstract-reaction/get-inbound-dependencies.md) | [jvm]<br>fun [getInboundDependencies](../-abstract-reaction/get-inbound-dependencies.md)(): ListSet<[Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)><br>abstract fun [getInboundDependencies](../../it.unibo.alchemist.model.interfaces/-reaction/get-inbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [getInputContext](../-abstract-reaction/get-input-context.md) | [jvm]<br>fun [getInputContext](../-abstract-reaction/get-input-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md)<br>abstract fun [getInputContext](../../it.unibo.alchemist.model.interfaces/-reaction/get-input-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getNode](../-navigation-prioritised-steering-with-physics/index.md#-1244046302%2FFunctions%2F-267951372) | [jvm]<br>fun [getNode](../-navigation-prioritised-steering-with-physics/index.md#-1244046302%2FFunctions%2F-267951372)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)><br>abstract fun [getNode](../../it.unibo.alchemist.model.interfaces/-reaction/get-node.md)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)> |
| [getOutboundDependencies](../-abstract-reaction/get-outbound-dependencies.md) | [jvm]<br>fun [getOutboundDependencies](../-abstract-reaction/get-outbound-dependencies.md)(): ListSet<[Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)><br>abstract fun [getOutboundDependencies](../../it.unibo.alchemist.model.interfaces/-reaction/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [getOutputContext](../-abstract-reaction/get-output-context.md) | [jvm]<br>fun [getOutputContext](../-abstract-reaction/get-output-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md)<br>abstract fun [getOutputContext](../../it.unibo.alchemist.model.interfaces/-reaction/get-output-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getRate](get-rate.md) | [jvm]<br>open fun [getRate](get-rate.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getTau](../-abstract-reaction/get-tau.md) | [jvm]<br>fun [getTau](../-abstract-reaction/get-tau.md)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)<br>abstract fun [getTau](../../it.unibo.alchemist.model.interfaces/-reaction/get-tau.md)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md) |
| [getTimeDistribution](../-navigation-prioritised-steering-with-physics/index.md#2053953683%2FFunctions%2F-267951372) | [jvm]<br>fun [getTimeDistribution](../-navigation-prioritised-steering-with-physics/index.md#2053953683%2FFunctions%2F-267951372)(): [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)><br>abstract fun [getTimeDistribution](../../it.unibo.alchemist.model.interfaces/-reaction/get-time-distribution.md)(): [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)> |
| [hashCode](../-abstract-reaction/hash-code.md) | [jvm]<br>fun [hashCode](../-abstract-reaction/hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [initializationComplete](../-abstract-reaction/initialization-complete.md) | [jvm]<br>open fun [initializationComplete](../-abstract-reaction/initialization-complete.md)(atTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>abstract fun [initializationComplete](../../it.unibo.alchemist.model.interfaces/-reaction/initialization-complete.md)(p: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), p1: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [setActions](../-s-a-p-e-r-e-gradient/index.md#2022331282%2FFunctions%2F-267951372) | [jvm]<br>open fun [setActions](../-s-a-p-e-r-e-gradient/index.md#2022331282%2FFunctions%2F-267951372)(actions: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Action](../../it.unibo.alchemist.model.interfaces/-action/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>>)<br>This should get overridden only if very tricky behaviours are implemented, such that the default Alchemist action addition model is no longer usable.<br>[jvm]<br>abstract fun [setActions](../../it.unibo.alchemist.model.interfaces/-reaction/set-actions.md)(p: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Action](../../it.unibo.alchemist.model.interfaces/-action/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>>) |
| [setConditions](../-s-a-p-e-r-e-gradient/index.md#1708622090%2FFunctions%2F-267951372) | [jvm]<br>open fun [setConditions](../-s-a-p-e-r-e-gradient/index.md#1708622090%2FFunctions%2F-267951372)(conditions: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>>)<br>This should get overridden only if very tricky behaviours are implemented, such that the default Alchemist condition addition model is no longer usable.<br>[jvm]<br>abstract fun [setConditions](../../it.unibo.alchemist.model.interfaces/-reaction/set-conditions.md)(p: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>>) |
| [toString](../-abstract-reaction/to-string.md) | [jvm]<br>open fun [toString](../-abstract-reaction/to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>the default implementation returns a String in the form className@timeScheduled[Conditions]-rate->[Actions] |
| [update](../-abstract-reaction/update.md) | [jvm]<br>fun [update](../-abstract-reaction/update.md)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), hasBeenExecuted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>abstract fun [update](../../it.unibo.alchemist.model.interfaces/-reaction/update.md)(p: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), p1: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), p2: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
---
title: AbstractReaction
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.reactions](../index.html)/[AbstractReaction](index.html)



# AbstractReaction



[jvm]\
abstract class [AbstractReaction](index.html)<[T](index.html)> : [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)> 

The type which describes the concentration of a molecule This class offers a partial implementation of Reaction. In particular, it allows to write new reaction specifying only which distribution time to adopt



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Constructors


| | |
|---|---|
| [AbstractReaction](-abstract-reaction.html) | [jvm]<br>open fun [AbstractReaction](-abstract-reaction.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>, timeDistribution: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>)<br>Builds a new reaction, starting at time t. |


## Functions


| Name | Summary |
|---|---|
| [canExecute](can-execute.html) | [jvm]<br>open fun [canExecute](can-execute.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>The default implementation verifies if all the conditions are valid. |
| [cloneOnNewNode](../../it.unibo.alchemist.model.interfaces/-reaction/clone-on-new-node.html) | [jvm]<br>abstract fun [cloneOnNewNode](../../it.unibo.alchemist.model.interfaces/-reaction/clone-on-new-node.html)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>, p1: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)> |
| [compareTo](compare-to.html) | [jvm]<br>fun [compareTo](compare-to.html)(o: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [equals](equals.html) | [jvm]<br>fun [equals](equals.html)(o: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [execute](execute.html) | [jvm]<br>open fun [execute](execute.html)()<br>The default execution iterates all the actions in order and executes them. |
| [getActions](../../it.unibo.alchemist.model.interfaces/-reaction/get-actions.html) | [jvm]<br>abstract fun [getActions](../../it.unibo.alchemist.model.interfaces/-reaction/get-actions.html)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>> |
| [getConditions](../../it.unibo.alchemist.model.interfaces/-reaction/get-conditions.html) | [jvm]<br>abstract fun [getConditions](../../it.unibo.alchemist.model.interfaces/-reaction/get-conditions.html)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>> |
| [getInboundDependencies](get-inbound-dependencies.html) | [jvm]<br>fun [getInboundDependencies](get-inbound-dependencies.html)(): ListSet<[Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [getInputContext](get-input-context.html) | [jvm]<br>fun [getInputContext](get-input-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getNode](../../it.unibo.alchemist.model.interfaces/-reaction/get-node.html) | [jvm]<br>abstract fun [getNode](../../it.unibo.alchemist.model.interfaces/-reaction/get-node.html)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)> |
| [getOutboundDependencies](get-outbound-dependencies.html) | [jvm]<br>fun [getOutboundDependencies](get-outbound-dependencies.html)(): ListSet<[Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [getOutputContext](get-output-context.html) | [jvm]<br>fun [getOutputContext](get-output-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getRate](../../it.unibo.alchemist.model.interfaces/-reaction/get-rate.html) | [jvm]<br>abstract fun [getRate](../../it.unibo.alchemist.model.interfaces/-reaction/get-rate.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getTau](get-tau.html) | [jvm]<br>fun [getTau](get-tau.html)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html) |
| [getTimeDistribution](../../it.unibo.alchemist.model.interfaces/-reaction/get-time-distribution.html) | [jvm]<br>abstract fun [getTimeDistribution](../../it.unibo.alchemist.model.interfaces/-reaction/get-time-distribution.html)(): [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)> |
| [hashCode](hash-code.html) | [jvm]<br>fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [initializationComplete](initialization-complete.html) | [jvm]<br>open fun [initializationComplete](initialization-complete.html)(atTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [setActions](../../it.unibo.alchemist.model.interfaces/-reaction/set-actions.html) | [jvm]<br>abstract fun [setActions](../../it.unibo.alchemist.model.interfaces/-reaction/set-actions.html)(p: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>>) |
| [setConditions](../../it.unibo.alchemist.model.interfaces/-reaction/set-conditions.html) | [jvm]<br>abstract fun [setConditions](../../it.unibo.alchemist.model.interfaces/-reaction/set-conditions.html)(p: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>>) |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>the default implementation returns a String in the form className@timeScheduled[Conditions]-rate->[Actions] |
| [update](update.html) | [jvm]<br>fun [update](update.html)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), hasBeenExecuted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |


## Properties


| Name | Summary |
|---|---|
| [actions](actions.html) | [jvm]<br>private open var [actions](actions.html): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<out [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>> |
| [conditions](conditions.html) | [jvm]<br>private open var [conditions](conditions.html): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<out [Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>> |
| [node](node.html) | [jvm]<br>private val [node](node.html): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)> |
| [timeDistribution](time-distribution.html) | [jvm]<br>private val [timeDistribution](time-distribution.html): [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)> |


## Inheritors


| Name |
|---|
| [CognitiveBehavior](../-cognitive-behavior/index.html) |
| [SteeringBehavior](../-steering-behavior/index.html) |
| [ChemicalReaction](../-chemical-reaction/index.html) |
| [Event](../-event/index.html) |
| [SAPEREGradient](../-s-a-p-e-r-e-gradient/index.html) |
| [SAPEREReaction](../-s-a-p-e-r-e-reaction/index.html) |


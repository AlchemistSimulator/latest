//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.reactions](../index.md)/[AbstractReaction](index.md)

# AbstractReaction

[jvm]\
abstract class [AbstractReaction](index.md)<[T](index.md)> : [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)> 

The type which describes the concentration of a molecule This class offers a partial implementation of Reaction. In particular, it allows to write new reaction specifying only which distribution time to adopt

## Parameters

jvm

| | |
|---|---|
| <T> | concentration type |

## Constructors

| | |
|---|---|
| [AbstractReaction](-abstract-reaction.md) | [jvm]<br>open fun [AbstractReaction](-abstract-reaction.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)>, timeDistribution: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)>)<br>Builds a new reaction, starting at time t. |

## Functions

| Name | Summary |
|---|---|
| [canExecute](can-execute.md) | [jvm]<br>open fun [canExecute](can-execute.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>The default implementation verifies if all the conditions are valid. |
| [cloneOnNewNode](../../it.unibo.alchemist.model.interfaces/-reaction/clone-on-new-node.md) | [jvm]<br>abstract fun [cloneOnNewNode](../../it.unibo.alchemist.model.interfaces/-reaction/clone-on-new-node.md)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)>, p1: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)> |
| [compareTo](compare-to.md) | [jvm]<br>fun [compareTo](compare-to.md)(o: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [equals](equals.md) | [jvm]<br>fun [equals](equals.md)(o: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [execute](execute.md) | [jvm]<br>open fun [execute](execute.md)()<br>The default execution iterates all the actions in order and executes them. |
| [getActions](../../it.unibo.alchemist.model.interfaces/-reaction/get-actions.md) | [jvm]<br>abstract fun [getActions](../../it.unibo.alchemist.model.interfaces/-reaction/get-actions.md)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Action](../../it.unibo.alchemist.model.interfaces/-action/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)>> |
| [getConditions](../../it.unibo.alchemist.model.interfaces/-reaction/get-conditions.md) | [jvm]<br>abstract fun [getConditions](../../it.unibo.alchemist.model.interfaces/-reaction/get-conditions.md)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)>> |
| [getInboundDependencies](get-inbound-dependencies.md) | [jvm]<br>fun [getInboundDependencies](get-inbound-dependencies.md)(): ListSet<[Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [getInputContext](get-input-context.md) | [jvm]<br>fun [getInputContext](get-input-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getNode](../../it.unibo.alchemist.model.interfaces/-reaction/get-node.md) | [jvm]<br>abstract fun [getNode](../../it.unibo.alchemist.model.interfaces/-reaction/get-node.md)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)> |
| [getOutboundDependencies](get-outbound-dependencies.md) | [jvm]<br>fun [getOutboundDependencies](get-outbound-dependencies.md)(): ListSet<[Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [getOutputContext](get-output-context.md) | [jvm]<br>fun [getOutputContext](get-output-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getRate](../../it.unibo.alchemist.model.interfaces/-reaction/get-rate.md) | [jvm]<br>abstract fun [getRate](../../it.unibo.alchemist.model.interfaces/-reaction/get-rate.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getTau](get-tau.md) | [jvm]<br>fun [getTau](get-tau.md)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md) |
| [getTimeDistribution](../../it.unibo.alchemist.model.interfaces/-reaction/get-time-distribution.md) | [jvm]<br>abstract fun [getTimeDistribution](../../it.unibo.alchemist.model.interfaces/-reaction/get-time-distribution.md)(): [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)> |
| [hashCode](hash-code.md) | [jvm]<br>fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [initializationComplete](initialization-complete.md) | [jvm]<br>open fun [initializationComplete](initialization-complete.md)(atTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [setActions](../../it.unibo.alchemist.model.interfaces/-reaction/set-actions.md) | [jvm]<br>abstract fun [setActions](../../it.unibo.alchemist.model.interfaces/-reaction/set-actions.md)(p: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Action](../../it.unibo.alchemist.model.interfaces/-action/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)>>) |
| [setConditions](../../it.unibo.alchemist.model.interfaces/-reaction/set-conditions.md) | [jvm]<br>abstract fun [setConditions](../../it.unibo.alchemist.model.interfaces/-reaction/set-conditions.md)(p: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)>>) |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>the default implementation returns a String in the form className@timeScheduled[Conditions]-rate->[Actions] |
| [update](update.md) | [jvm]<br>fun [update](update.md)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), hasBeenExecuted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |

## Properties

| Name | Summary |
|---|---|
| [actions](actions.md) | [jvm]<br>private open var [actions](actions.md): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<out [Action](../../it.unibo.alchemist.model.interfaces/-action/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)>> |
| [conditions](conditions.md) | [jvm]<br>private open var [conditions](conditions.md): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<out [Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)>> |
| [node](node.md) | [jvm]<br>private val [node](node.md): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)> |
| [timeDistribution](time-distribution.md) | [jvm]<br>private val [timeDistribution](time-distribution.md): [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.md)<[T](../../it.unibo.alchemist/-supported-incarnations/get.md)> |

## Inheritors

| Name |
|---|
| [CognitiveBehavior](../-cognitive-behavior/index.md) |
| [SteeringBehavior](../-steering-behavior/index.md) |
| [ChemicalReaction](../-chemical-reaction/index.md) |
| [Event](../-event/index.md) |
| [SAPEREGradient](../-s-a-p-e-r-e-gradient/index.md) |
| [SAPEREReaction](../-s-a-p-e-r-e-reaction/index.md) |

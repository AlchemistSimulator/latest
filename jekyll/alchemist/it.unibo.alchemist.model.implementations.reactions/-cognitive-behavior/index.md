---
title: CognitiveBehavior
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.reactions](../index.html)/[CognitiveBehavior](index.html)



# CognitiveBehavior



[jvm]\
class [CognitiveBehavior](index.html)<[T](index.html), [V](index.html) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[V](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[V](index.html)>>(**pedestrian**: [CognitivePedestrian](../../it.unibo.alchemist.model.interfaces/-cognitive-pedestrian/index.html)<[T](index.html), [V](index.html), [A](index.html)>, **timeDistribution**: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](index.html)>) : [AbstractReaction](../-abstract-reaction/index.html)<[T](index.html)> 

Reaction representing the cognitive behavior of a pedestrian.



## Parameters


jvm

| | |
|---|---|
| pedestrian | the owner of this reaction. |
| timeDistribution | the time distribution according to this the reaction executes. |



## Constructors


| | |
|---|---|
| [CognitiveBehavior](-cognitive-behavior.html) | [jvm]<br>fun <[T](index.html), [V](index.html) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[V](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[V](index.html)>> [CognitiveBehavior](-cognitive-behavior.html)(pedestrian: [CognitivePedestrian](../../it.unibo.alchemist.model.interfaces/-cognitive-pedestrian/index.html)<[T](index.html), [V](index.html), [A](index.html)>, timeDistribution: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](index.html)>)<br>    the owner of this reaction. |


## Functions


| Name | Summary |
|---|---|
| [addInboundDependency](../-navigation-prioritised-steering-with-physics/index.html#-1772000845%2FFunctions%2F-134779887) | [jvm]<br>fun [addInboundDependency](../-navigation-prioritised-steering-with-physics/index.html#-1772000845%2FFunctions%2F-134779887)(p0: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)) |
| [addOutboundDependency](../-navigation-prioritised-steering-with-physics/index.html#-2022076396%2FFunctions%2F-134779887) | [jvm]<br>fun [addOutboundDependency](../-navigation-prioritised-steering-with-physics/index.html#-2022076396%2FFunctions%2F-134779887)(p0: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)) |
| [canExecute](../-abstract-reaction/can-execute.html) | [jvm]<br>open override fun [canExecute](../-abstract-reaction/can-execute.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [cloneOnNewNode](clone-on-new-node.html) | [jvm]<br>open override fun [cloneOnNewNode](clone-on-new-node.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>?, currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)?): [CognitiveBehavior](index.html)<[T](index.html), [V](index.html), [A](index.html)> |
| [compareTo](../-navigation-prioritised-steering-with-physics/index.html#588180668%2FFunctions%2F-134779887) | [jvm]<br>operator override fun [compareTo](../-navigation-prioritised-steering-with-physics/index.html#588180668%2FFunctions%2F-134779887)(other: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [equals](../-navigation-prioritised-steering-with-physics/index.html#-267299839%2FFunctions%2F-134779887) | [jvm]<br>operator override fun [equals](../-navigation-prioritised-steering-with-physics/index.html#-267299839%2FFunctions%2F-134779887)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [execute](../-abstract-reaction/execute.html) | [jvm]<br>open override fun [execute](../-abstract-reaction/execute.html)() |
| [getActions](../-navigation-prioritised-steering-with-physics/index.html#13515737%2FFunctions%2F-134779887) | [jvm]<br>open override fun [getActions](../-navigation-prioritised-steering-with-physics/index.html#13515737%2FFunctions%2F-134779887)(): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](index.html)>> |
| [getConditions](../-navigation-prioritised-steering-with-physics/index.html#-184159508%2FFunctions%2F-134779887) | [jvm]<br>open override fun [getConditions](../-navigation-prioritised-steering-with-physics/index.html#-184159508%2FFunctions%2F-134779887)(): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.html)<[T](index.html)>> |
| [getInboundDependencies](../-abstract-reaction/get-inbound-dependencies.html) | [jvm]<br>override fun [getInboundDependencies](../-abstract-reaction/get-inbound-dependencies.html)(): ListSet<[Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [getInputContext](../-abstract-reaction/get-input-context.html) | [jvm]<br>override fun [getInputContext](../-abstract-reaction/get-input-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getNode](../-navigation-prioritised-steering-with-physics/index.html#-1244046302%2FFunctions%2F-134779887) | [jvm]<br>override fun [getNode](../-navigation-prioritised-steering-with-physics/index.html#-1244046302%2FFunctions%2F-134779887)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)> |
| [getOutboundDependencies](../-abstract-reaction/get-outbound-dependencies.html) | [jvm]<br>override fun [getOutboundDependencies](../-abstract-reaction/get-outbound-dependencies.html)(): ListSet<[Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [getOutputContext](../-abstract-reaction/get-output-context.html) | [jvm]<br>override fun [getOutputContext](../-abstract-reaction/get-output-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getRate](get-rate.html) | [jvm]<br>open override fun [getRate](get-rate.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getRateAsString](../-navigation-prioritised-steering-with-physics/index.html#-166271391%2FFunctions%2F-134779887) | [jvm]<br>open fun [getRateAsString](../-navigation-prioritised-steering-with-physics/index.html#-166271391%2FFunctions%2F-134779887)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getReactionName](../-navigation-prioritised-steering-with-physics/index.html#494389008%2FFunctions%2F-134779887) | [jvm]<br>open fun [getReactionName](../-navigation-prioritised-steering-with-physics/index.html#494389008%2FFunctions%2F-134779887)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getTau](../-abstract-reaction/get-tau.html) | [jvm]<br>override fun [getTau](../-abstract-reaction/get-tau.html)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html) |
| [getTimeDistribution](../-navigation-prioritised-steering-with-physics/index.html#2053953683%2FFunctions%2F-134779887) | [jvm]<br>override fun [getTimeDistribution](../-navigation-prioritised-steering-with-physics/index.html#2053953683%2FFunctions%2F-134779887)(): [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](index.html)> |
| [hashCode](../-abstract-reaction/hash-code.html) | [jvm]<br>override fun [hashCode](../-abstract-reaction/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [initializationComplete](../-navigation-prioritised-steering-with-physics/index.html#496764034%2FFunctions%2F-134779887) | [jvm]<br>open override fun [initializationComplete](../-navigation-prioritised-steering-with-physics/index.html#496764034%2FFunctions%2F-134779887)(p0: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), p1: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), *>) |
| [makeClone](../-navigation-prioritised-steering-with-physics/index.html#1151787077%2FFunctions%2F-134779887) | [jvm]<br>open fun <[R](../-navigation-prioritised-steering-with-physics/index.html#1151787077%2FFunctions%2F-134779887) : [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>> [makeClone](../-navigation-prioritised-steering-with-physics/index.html#1151787077%2FFunctions%2F-134779887)(p0: [Supplier](https://docs.oracle.com/javase/8/docs/api/java/util/function/Supplier.html)<[R](../-navigation-prioritised-steering-with-physics/index.html#1151787077%2FFunctions%2F-134779887)>): [R](../-navigation-prioritised-steering-with-physics/index.html#1151787077%2FFunctions%2F-134779887) |
| [setActions](../-navigation-prioritised-steering-with-physics/index.html#1557798850%2FFunctions%2F-134779887) | [jvm]<br>open override fun [setActions](../-navigation-prioritised-steering-with-physics/index.html#1557798850%2FFunctions%2F-134779887)(p0: [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](index.html)>>) |
| [setConditions](../-navigation-prioritised-steering-with-physics/index.html#-1302498472%2FFunctions%2F-134779887) | [jvm]<br>open override fun [setConditions](../-navigation-prioritised-steering-with-physics/index.html#-1302498472%2FFunctions%2F-134779887)(p0: [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.html)<[T](index.html)>>) |
| [setInputContext](../-navigation-prioritised-steering-with-physics/index.html#-1096973185%2FFunctions%2F-134779887) | [jvm]<br>fun [setInputContext](../-navigation-prioritised-steering-with-physics/index.html#-1096973185%2FFunctions%2F-134779887)(p0: [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html)) |
| [setOutputContext](../-navigation-prioritised-steering-with-physics/index.html#-1034313602%2FFunctions%2F-134779887) | [jvm]<br>fun [setOutputContext](../-navigation-prioritised-steering-with-physics/index.html#-1034313602%2FFunctions%2F-134779887)(p0: [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html)) |
| [toString](../-abstract-reaction/to-string.html) | [jvm]<br>open override fun [toString](../-abstract-reaction/to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [update](../-navigation-prioritised-steering-with-physics/index.html#-1541973436%2FFunctions%2F-134779887) | [jvm]<br>override fun [update](../-navigation-prioritised-steering-with-physics/index.html#-1541973436%2FFunctions%2F-134779887)(p0: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), p1: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), p2: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), *>) |


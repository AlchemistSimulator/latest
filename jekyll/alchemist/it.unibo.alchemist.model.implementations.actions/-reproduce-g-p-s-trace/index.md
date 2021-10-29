---
title: ReproduceGPSTrace
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[ReproduceGPSTrace](index.html)



# ReproduceGPSTrace



[jvm]\
open class [ReproduceGPSTrace](index.html)<[T](index.html)> : [MoveOnMapWithGPS](../-move-on-map-with-g-p-s/index.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)>



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Constructors


| | |
|---|---|
| [ReproduceGPSTrace](-reproduce-g-p-s-trace.html) | [jvm]<br>open fun [ReproduceGPSTrace](-reproduce-g-p-s-trace.html)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)>, path: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), cycle: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), normalizer: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), normalizerArgs: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>the environment |
| [ReproduceGPSTrace](-reproduce-g-p-s-trace.html) | [jvm]<br>open fun [ReproduceGPSTrace](-reproduce-g-p-s-trace.html)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)>, speed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), path: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), cycle: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), normalizer: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), normalizerArgs: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>the environment |


## Functions


| Name | Summary |
|---|---|
| [cloneAction](../-move-on-map/clone-action.html) | [jvm]<br>open fun [cloneAction](../-move-on-map/clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)>): [MoveOnMap](../-move-on-map/index.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)><br>Fails, can't be cloned.<br>[jvm]<br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.html)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)> |
| [execute](../-abstract-move-node/execute.html) | [jvm]<br>open fun [execute](../-abstract-move-node/execute.html)() |
| [getContext](../-abstract-move-node/get-context.html) | [jvm]<br>fun [getContext](../-abstract-move-node/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getEnvironment](../-move-on-map/get-environment.html) | [jvm]<br>fun [getEnvironment](../-move-on-map/get-environment.html)(): [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)> |
| [getNextPosition](../-abstract-configurable-move-node/get-next-position.html) | [jvm]<br>fun [getNextPosition](../-abstract-configurable-move-node/get-next-position.html)(): [P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [toString](../-abstract-action/to-string.html) | [jvm]<br>open fun [toString](../-abstract-action/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [traceFor](../-move-on-map-with-g-p-s/trace-for.html) | [jvm]<br>open fun [traceFor](../-move-on-map-with-g-p-s/trace-for.html)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, path: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), cycle: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), normalizer: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), normalizerArgs: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.html)<br>the environment |


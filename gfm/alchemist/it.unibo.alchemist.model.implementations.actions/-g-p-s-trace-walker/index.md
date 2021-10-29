//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[GPSTraceWalker](index.md)

# GPSTraceWalker

[jvm]\
class [GPSTraceWalker](index.md)<[T](index.md)> : [MoveOnMapWithGPS](../-move-on-map-with-g-p-s/index.md)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.md)> 

A walker that follows a trace. The trace is mandatory.

## Parameters

jvm

| | |
|---|---|
| <T> | Concentration Time |

## Constructors

| | |
|---|---|
| [GPSTraceWalker](-g-p-s-trace-walker.md) | [jvm]<br>open fun [GPSTraceWalker](-g-p-s-trace-walker.md)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.md)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.md)>, path: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), cycle: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), normalizer: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), normalizerArgs: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>the environment |

## Functions

| Name | Summary |
|---|---|
| [cloneAction](clone-action.md) | [jvm]<br>open fun [cloneAction](clone-action.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.md)>): [GPSTraceWalker](index.md)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.md)><br>Fails, can't be cloned.<br>[jvm]<br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.md)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.md)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.md)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.md)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.md)> |
| [execute](../-abstract-move-node/execute.md) | [jvm]<br>open fun [execute](../-abstract-move-node/execute.md)() |
| [getContext](../-abstract-move-node/get-context.md) | [jvm]<br>fun [getContext](../-abstract-move-node/get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getEnvironment](../-move-on-map/get-environment.md) | [jvm]<br>fun [getEnvironment](../-move-on-map/get-environment.md)(): [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.md)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.md)> |
| [getNextPosition](../-abstract-configurable-move-node/get-next-position.md) | [jvm]<br>fun [getNextPosition](../-abstract-configurable-move-node/get-next-position.md)(): [P](../../it.unibo.alchemist.loader.deployments/-deployment/index.md) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [toString](../-abstract-action/to-string.md) | [jvm]<br>open fun [toString](../-abstract-action/to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [traceFor](../-move-on-map-with-g-p-s/trace-for.md) | [jvm]<br>open fun [traceFor](../-move-on-map-with-g-p-s/trace-for.md)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, path: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), cycle: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), normalizer: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), normalizerArgs: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.md)<br>the environment |

---
title: GPSTraceWalker
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[GPSTraceWalker](index.html)/[GPSTraceWalker](-g-p-s-trace-walker.html)



# GPSTraceWalker



[jvm]\
open fun [GPSTraceWalker](-g-p-s-trace-walker.html)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[T](../-reproduce-g-p-s-trace/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../-reproduce-g-p-s-trace/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../-reproduce-g-p-s-trace/index.html)>, path: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), cycle: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), normalizer: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), normalizerArgs: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)



## Parameters


jvm

| | |
|---|---|
| environment | the environment |
| node | the node |
| reaction | the reaction |
| path | resource(file, directory, ...) with GPS trace |
| cycle | true if the traces have to be distributed cyclically |
| normalizer | name of the class that implement the strategy to normalize the time |
| normalizerArgs | Args to build normalize |





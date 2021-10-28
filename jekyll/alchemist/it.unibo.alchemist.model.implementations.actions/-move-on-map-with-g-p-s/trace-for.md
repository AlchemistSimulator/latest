---
title: traceFor
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[MoveOnMapWithGPS](index.html)/[traceFor](trace-for.html)



# traceFor



[jvm]\
open fun [traceFor](trace-for.html)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, path: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), cycle: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), normalizer: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), normalizerArgs: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.html)



#### Return



the GPSTrace



## Parameters


jvm

| | |
|---|---|
| environment | the environment |
| path | resource(file, directory, ...) with GPS trace |
| cycle | true if the traces have to be distributed cyclically |
| normalizer | name of the class that implement the strategy to normalize the time |
| normalizerArgs | Args to build normalize |





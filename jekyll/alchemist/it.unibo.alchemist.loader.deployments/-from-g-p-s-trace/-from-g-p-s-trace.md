---
title: FromGPSTrace
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.deployments](../index.html)/[FromGPSTrace](index.html)/[FromGPSTrace](-from-g-p-s-trace.html)



# FromGPSTrace



[jvm]\
open fun [FromGPSTrace](-from-g-p-s-trace.html)(nodeCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), path: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), cycle: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), normalizer: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), args: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)



## Parameters


jvm

| | |
|---|---|
| nodeCount | number of node request |
| path | path with the gps tracks |
| cycle | true if considering list of GPSTrace cycle, default false |
| normalizer | class to use to normalize time |
| args | args to use to create GPSTimeNormalizer |



#### Throws


| | |
|---|---|
| [java.io.IOException](https://docs.oracle.com/javase/8/docs/api/java/io/IOException.html) | if there are errors accessing the file system |




---
title: extractData
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.export](../index.html)/[ExecutionTime](index.html)/[extractData](extract-data.html)



# extractData



[jvm]\
open fun <[T](extract-data.html)> [extractData](extract-data.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)>, time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), step: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>



Extracts numeric properties from an environment.



#### Return



the extracted properties



## Parameters


jvm

| | |
|---|---|
| environment | the [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html) |
| reaction | the last executed [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html) |
| time | the current [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html) |
| step | the simulation step |
| <T> | concentration type |





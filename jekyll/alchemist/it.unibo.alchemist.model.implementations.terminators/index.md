---
title: it.unibo.alchemist.model.implementations.terminators
---
//[alchemist](../../index.html)/[it.unibo.alchemist.model.implementations.terminators](index.html)



# Package it.unibo.alchemist.model.implementations.terminators



## Types


| Name | Summary |
|---|---|
| [AfterTime](-after-time/index.html) | [jvm]<br>class [AfterTime](-after-time/index.html)(**endTime**: [Time](../it.unibo.alchemist.model.interfaces/-time/index.html)) : [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](../it.unibo.alchemist.model.interfaces/-environment/index.html)<*, *>> |
| [StableForSteps](-stable-for-steps/index.html) | [jvm]<br>class [StableForSteps](-stable-for-steps/index.html)<[T](-stable-for-steps/index.html)>(**checkInterval**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **equalIntervals**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) : [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](-stable-for-steps/index.html), *>> <br>A [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html) that [tests](-stable-for-steps/test.html) if an environment's nodes (meaning their position and concentration) have remained unchanged for a certain amount of steps. |


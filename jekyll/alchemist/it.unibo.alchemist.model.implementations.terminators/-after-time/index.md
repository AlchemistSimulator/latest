---
title: AfterTime
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.terminators](../index.html)/[AfterTime](index.html)



# AfterTime



[jvm]\
class [AfterTime](index.html)(**endTime**: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)) : [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<*, *>>



## Parameters


jvm

| | |
|---|---|
| endTime | the end time. |



## Constructors


| | |
|---|---|
| [AfterTime](-after-time.html) | [jvm]<br>fun [AfterTime](-after-time.html)(endTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html))<br>the end time. |


## Functions


| Name | Summary |
|---|---|
| [and](index.html#-844180402%2FFunctions%2F-134779887) | [jvm]<br>open fun [and](index.html#-844180402%2FFunctions%2F-134779887)(p0: [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<in [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<*, *>>): [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<*, *>> |
| [negate](../-stable-for-steps/index.html#600125100%2FFunctions%2F-134779887) | [jvm]<br>open fun [negate](../-stable-for-steps/index.html#600125100%2FFunctions%2F-134779887)(): [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<*, *>> |
| [or](index.html#-928151932%2FFunctions%2F-134779887) | [jvm]<br>open fun [or](index.html#-928151932%2FFunctions%2F-134779887)(p0: [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<in [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<*, *>>): [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<*, *>> |
| [test](test.html) | [jvm]<br>open override fun [test](test.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<*, *>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Tries to access the simulation time from the [environment](test.html). |


## Properties


| Name | Summary |
|---|---|
| [endTime](end-time.html) | [jvm]<br>val [endTime](end-time.html): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)<br>the end time. |


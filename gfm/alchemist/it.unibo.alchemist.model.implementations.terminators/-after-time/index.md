//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.terminators](../index.md)/[AfterTime](index.md)

# AfterTime

[jvm]\
class [AfterTime](index.md)(**endTime**: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)) : [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<*, *>>

## Parameters

jvm

| | |
|---|---|
| endTime | the end time. |

## Constructors

| | |
|---|---|
| [AfterTime](-after-time.md) | [jvm]<br>fun [AfterTime](-after-time.md)(endTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md))<br>the end time. |

## Functions

| Name | Summary |
|---|---|
| [and](index.md#-844180402%2FFunctions%2F-267951372) | [jvm]<br>open fun [and](index.md#-844180402%2FFunctions%2F-267951372)(p0: [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<in [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<*, *>>): [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<*, *>> |
| [negate](../-stable-for-steps/index.md#600125100%2FFunctions%2F-267951372) | [jvm]<br>open fun [negate](../-stable-for-steps/index.md#600125100%2FFunctions%2F-267951372)(): [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<*, *>> |
| [or](index.md#-928151932%2FFunctions%2F-267951372) | [jvm]<br>open fun [or](index.md#-928151932%2FFunctions%2F-267951372)(p0: [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<in [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<*, *>>): [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<*, *>> |
| [test](test.md) | [jvm]<br>open override fun [test](test.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<*, *>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Tries to access the simulation time from the [environment](test.md). |

## Properties

| Name | Summary |
|---|---|
| [endTime](end-time.md) | [jvm]<br>val [endTime](end-time.md): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)<br>the end time. |

//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.terminators](../index.md)/[StableForSteps](index.md)

# StableForSteps

[jvm]\
class [StableForSteps](index.md)<[T](index.md)>(**checkInterval**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **equalIntervals**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) : [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), *>> 

A [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html) that [tests](test.md) if an environment's nodes (meaning their position and concentration) have remained unchanged for a certain amount of steps.

The check isn't performed on every [step](../../it.unibo.alchemist.core.interfaces/-simulation/get-step.md) of a [simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.md), instead an interval that determines how many steps are to be skipped between each check is specified. For [test](test.md) to return true, an environment must remain unchanged for checkInterval * equalIntervals steps. This result might not be entirely consistent, since the check isn't performed every step so as not to cause performance issues. Therefore it might happen that some changes occur in the environment but are reverted before the next check is performed.

[test](test.md) should be called at every step of the simulation in order to avoid missing checks.

## Parameters

jvm

| | |
|---|---|
| checkInterval | The recurrence of the test |
| equalIntervals | The amount of checkInterval intervals that need to pass (during which the environment doesn't change) for [test](test.md) to return true |

## Constructors

| | |
|---|---|
| [StableForSteps](-stable-for-steps.md) | [jvm]<br>fun [StableForSteps](-stable-for-steps.md)(checkInterval: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), equalIntervals: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))<br>Creates a new [StableForSteps](index.md) with the given values. |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [jvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [and](index.md#2145138100%2FFunctions%2F-267951372) | [jvm]<br>open fun [and](index.md#2145138100%2FFunctions%2F-267951372)(p0: [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<in [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), *>>): [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), *>> |
| [negate](index.md#600125100%2FFunctions%2F-267951372) | [jvm]<br>open fun [negate](index.md#600125100%2FFunctions%2F-267951372)(): [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), *>> |
| [or](index.md#-290347670%2FFunctions%2F-267951372) | [jvm]<br>open fun [or](index.md#-290347670%2FFunctions%2F-267951372)(p0: [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<in [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), *>>): [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), *>> |
| [test](test.md) | [jvm]<br>open override fun [test](test.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), *>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

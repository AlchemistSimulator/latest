---
title: StableForSteps
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.terminators](../index.html)/[StableForSteps](index.html)



# StableForSteps



[jvm]\
class [StableForSteps](index.html)<[T](index.html)>(**checkInterval**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **equalIntervals**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) : [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), *>> 

A [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html) that [tests](test.html) if an environment's nodes (meaning their position and concentration) have remained unchanged for a certain amount of steps.



The check isn't performed on every [step](../../it.unibo.alchemist.core.interfaces/-simulation/get-step.html) of a [simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.html), instead an interval that determines how many steps are to be skipped between each check is specified. For [test](test.html) to return true, an environment must remain unchanged for checkInterval * equalIntervals steps. This result might not be entirely consistent, since the check isn't performed every step so as not to cause performance issues. Therefore it might happen that some changes occur in the environment but are reverted before the next check is performed.



[test](test.html) should be called at every step of the simulation in order to avoid missing checks.



## Parameters


jvm

| | |
|---|---|
| checkInterval | The recurrence of the test |
| equalIntervals | The amount of checkInterval intervals that need to pass (during which the environment doesn't change) for [test](test.html) to return true |



## Constructors


| | |
|---|---|
| [StableForSteps](-stable-for-steps.html) | [jvm]<br>fun [StableForSteps](-stable-for-steps.html)(checkInterval: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), equalIntervals: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))<br>Creates a new [StableForSteps](index.html) with the given values. |


## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [and](index.html#2145138100%2FFunctions%2F-134779887) | [jvm]<br>open fun [and](index.html#2145138100%2FFunctions%2F-134779887)(p0: [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<in [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), *>>): [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), *>> |
| [negate](index.html#600125100%2FFunctions%2F-134779887) | [jvm]<br>open fun [negate](index.html#600125100%2FFunctions%2F-134779887)(): [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), *>> |
| [or](index.html#-290347670%2FFunctions%2F-134779887) | [jvm]<br>open fun [or](index.html#-290347670%2FFunctions%2F-134779887)(p0: [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<in [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), *>>): [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), *>> |
| [test](test.html) | [jvm]<br>open override fun [test](test.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), *>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |


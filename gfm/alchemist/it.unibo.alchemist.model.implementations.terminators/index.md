//[alchemist](../../index.md)/[it.unibo.alchemist.model.implementations.terminators](index.md)

# Package it.unibo.alchemist.model.implementations.terminators

## Types

| Name | Summary |
|---|---|
| [AfterTime](-after-time/index.md) | [jvm]<br>class [AfterTime](-after-time/index.md)(**endTime**: [Time](../it.unibo.alchemist.model.interfaces/-time/index.md)) : [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](../it.unibo.alchemist.model.interfaces/-environment/index.md)<*, *>> |
| [StableForSteps](-stable-for-steps/index.md) | [jvm]<br>class [StableForSteps](-stable-for-steps/index.md)<[T](-stable-for-steps/index.md)>(**checkInterval**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **equalIntervals**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) : [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](-stable-for-steps/index.md), *>> <br>A [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html) that [tests](-stable-for-steps/test.md) if an environment's nodes (meaning their position and concentration) have remained unchanged for a certain amount of steps. |

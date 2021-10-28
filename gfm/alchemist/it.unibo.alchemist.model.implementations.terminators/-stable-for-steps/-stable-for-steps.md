//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.terminators](../index.md)/[StableForSteps](index.md)/[StableForSteps](-stable-for-steps.md)

# StableForSteps

[jvm]\
fun [StableForSteps](-stable-for-steps.md)(checkInterval: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), equalIntervals: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))

Creates a new [StableForSteps](index.md) with the given values.

## Parameters

jvm

| | |
|---|---|
| checkInterval | The recurrence of the test |
| equalIntervals | The amount of checkInterval intervals that need to pass (during which the environment doesn't change) for [test](test.md) to return true |

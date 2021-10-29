//[alchemist](../../../index.md)/[it.unibo.alchemist.core.implementations](../index.md)/[Engine](index.md)/[Engine](-engine.md)

# Engine

[jvm]\
open fun [Engine](-engine.md)(e: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../-array-indexed-priority-queue/index.md), [P](index.md)>)

Builds a simulation for a given environment. By default it uses a DependencyGraph and an IndexedPriorityQueue internally. If you want to use your own implementations of [DependencyGraph](../../it.unibo.alchemist.core.interfaces/-dependency-graph/index.md) and [Scheduler](../../it.unibo.alchemist.core.interfaces/-scheduler/index.md) interfaces, don't use this constructor.

## Parameters

jvm

| | |
|---|---|
| e | the environment at the initial time |

[jvm]\
open fun [Engine](-engine.md)(e: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../-array-indexed-priority-queue/index.md), [P](index.md)>, maxSteps: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))

Builds a simulation for a given environment. By default it uses a DependencyGraph and an IndexedPriorityQueue internally. If you want to use your own implementations of [DependencyGraph](../../it.unibo.alchemist.core.interfaces/-dependency-graph/index.md) and [Scheduler](../../it.unibo.alchemist.core.interfaces/-scheduler/index.md) interfaces, don't use this constructor.

## Parameters

jvm

| | |
|---|---|
| e | the environment at the initial time |
| maxSteps | the maximum number of steps to do |

[jvm]\
open fun [Engine](-engine.md)(e: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../-array-indexed-priority-queue/index.md), [P](index.md)>, maxSteps: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), t: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md))

Builds a simulation for a given environment. By default it uses a DependencyGraph and an IndexedPriorityQueue internally. If you want to use your own implementations of [DependencyGraph](../../it.unibo.alchemist.core.interfaces/-dependency-graph/index.md) and [Scheduler](../../it.unibo.alchemist.core.interfaces/-scheduler/index.md) interfaces, don't use this constructor.

## Parameters

jvm

| | |
|---|---|
| e | the environment at the initial time |
| maxSteps | the maximum number of steps to do |
| t | the maximum time to reach |

[jvm]\
open fun [Engine](-engine.md)(e: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../-array-indexed-priority-queue/index.md), [P](index.md)>, t: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md))

Builds a simulation for a given environment. By default it uses a DependencyGraph and an IndexedPriorityQueue internally. If you want to use your own implementations of [DependencyGraph](../../it.unibo.alchemist.core.interfaces/-dependency-graph/index.md) and [Scheduler](../../it.unibo.alchemist.core.interfaces/-scheduler/index.md) interfaces, don't use this constructor.

## Parameters

jvm

| | |
|---|---|
| e | the environment at the initial time |
| t | the maximum time to reach |

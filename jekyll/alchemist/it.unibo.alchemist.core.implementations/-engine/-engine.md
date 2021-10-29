---
title: Engine
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.core.implementations](../index.html)/[Engine](index.html)/[Engine](-engine.html)



# Engine



[jvm]\
open fun [Engine](-engine.html)(e: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](index.html)>)



Builds a simulation for a given environment. By default it uses a DependencyGraph and an IndexedPriorityQueue internally. If you want to use your own implementations of [DependencyGraph](../../it.unibo.alchemist.core.interfaces/-dependency-graph/index.html) and [Scheduler](../../it.unibo.alchemist.core.interfaces/-scheduler/index.html) interfaces, don't use this constructor.



## Parameters


jvm

| | |
|---|---|
| e | the environment at the initial time |





[jvm]\
open fun [Engine](-engine.html)(e: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](index.html)>, maxSteps: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))



Builds a simulation for a given environment. By default it uses a DependencyGraph and an IndexedPriorityQueue internally. If you want to use your own implementations of [DependencyGraph](../../it.unibo.alchemist.core.interfaces/-dependency-graph/index.html) and [Scheduler](../../it.unibo.alchemist.core.interfaces/-scheduler/index.html) interfaces, don't use this constructor.



## Parameters


jvm

| | |
|---|---|
| e | the environment at the initial time |
| maxSteps | the maximum number of steps to do |





[jvm]\
open fun [Engine](-engine.html)(e: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](index.html)>, maxSteps: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), t: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html))



Builds a simulation for a given environment. By default it uses a DependencyGraph and an IndexedPriorityQueue internally. If you want to use your own implementations of [DependencyGraph](../../it.unibo.alchemist.core.interfaces/-dependency-graph/index.html) and [Scheduler](../../it.unibo.alchemist.core.interfaces/-scheduler/index.html) interfaces, don't use this constructor.



## Parameters


jvm

| | |
|---|---|
| e | the environment at the initial time |
| maxSteps | the maximum number of steps to do |
| t | the maximum time to reach |





[jvm]\
open fun [Engine](-engine.html)(e: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](index.html)>, t: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html))



Builds a simulation for a given environment. By default it uses a DependencyGraph and an IndexedPriorityQueue internally. If you want to use your own implementations of [DependencyGraph](../../it.unibo.alchemist.core.interfaces/-dependency-graph/index.html) and [Scheduler](../../it.unibo.alchemist.core.interfaces/-scheduler/index.html) interfaces, don't use this constructor.



## Parameters


jvm

| | |
|---|---|
| e | the environment at the initial time |
| t | the maximum time to reach |





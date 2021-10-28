---
title: AnyRealDistribution
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.timedistributions](../index.html)/[AnyRealDistribution](index.html)/[AnyRealDistribution](-any-real-distribution.html)



# AnyRealDistribution



[jvm]\
open fun [AnyRealDistribution](-any-real-distribution.html)(rng: RandomGenerator, distribution: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), parameters: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>)



## Parameters


jvm

| | |
|---|---|
| rng | the RandomGenerator |
| distribution | the distribution name (case insensitive). Must be mappable to an entity implementing RealDistribution |
| parameters | the parameters for the distribution |





[jvm]\
open fun [AnyRealDistribution](-any-real-distribution.html)(start: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), rng: RandomGenerator, distribution: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), parameters: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>)



## Parameters


jvm

| | |
|---|---|
| start | the initial time |
| rng | the RandomGenerator |
| distribution | the distribution name (case insensitive). Must be mappable to an entity implementing RealDistribution |
| parameters | the parameters for the distribution |





[jvm]\
open fun [AnyRealDistribution](-any-real-distribution.html)(distribution: RealDistribution)



## Parameters


jvm

| | |
|---|---|
| distribution | the [AnyRealDistribution](index.html) to use. To ensure reproducibility, such distribution must get created using the simulation RandomGenerator. |





[jvm]\
open fun [AnyRealDistribution](-any-real-distribution.html)(start: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), distribution: RealDistribution)



## Parameters


jvm

| | |
|---|---|
| start | distribution start time |
| distribution | the [AnyRealDistribution](index.html) to use. To ensure reproducibility, such distribution must get created using the simulation RandomGenerator. |





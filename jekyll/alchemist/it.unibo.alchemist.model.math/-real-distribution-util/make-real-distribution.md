---
title: makeRealDistribution
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.math](../index.html)/[RealDistributionUtil](index.html)/[makeRealDistribution](make-real-distribution.html)



# makeRealDistribution



[jvm]\
open fun [makeRealDistribution](make-real-distribution.html)(randomGenerator: RandomGenerator, shortname: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), arguments: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>): RealDistribution



#### Return



the created RealDistribution



## Parameters


jvm

| | |
|---|---|
| randomGenerator | the RandomGenerator |
| shortname | the distribution name (case insensitive). Must be mappable to an entity implementing RealDistribution |
| arguments | the parameters for the distribution |



#### Throws


| | |
|---|---|
| [java.lang.IllegalArgumentException](https://docs.oracle.com/javase/8/docs/api/java/lang/IllegalArgumentException.html) | if the creation can't be completed for any reason |




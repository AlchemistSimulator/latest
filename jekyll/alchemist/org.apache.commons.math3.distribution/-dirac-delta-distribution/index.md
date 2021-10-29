---
title: DiracDeltaDistribution
---
//[alchemist](../../../index.html)/[org.apache.commons.math3.distribution](../index.html)/[DiracDeltaDistribution](index.html)



# DiracDeltaDistribution



[jvm]\
class [DiracDeltaDistribution](index.html)(**value**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : RealDistribution, [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Models a Real Distribution backed by a Dirac Delta Function. This is similar to a Logistic probability function with a shape whose value tends to zero.



In practice, samples from this function return the provided [value](value.html) as a constant. The variance is zero, there is no randomness involved, and most of the useful information of a real distribution are actually lost. However, this utility can transform tools meant to work with a probability function in such a way that they work with a constant value (e.g., random walks with a constant step).



## Constructors


| | |
|---|---|
| [DiracDeltaDistribution](-dirac-delta-distribution.html) | [jvm]<br>fun [DiracDeltaDistribution](-dirac-delta-distribution.html)(randomGenerator: RandomGenerator? = null, value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>This constructor is meant for reflection compatibility only. |
| [DiracDeltaDistribution](-dirac-delta-distribution.html) | [jvm]<br>fun [DiracDeltaDistribution](-dirac-delta-distribution.html)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |


## Functions


| Name | Summary |
|---|---|
| [cumulativeProbability](cumulative-probability.html) | [jvm]<br>open override fun [cumulativeProbability](cumulative-probability.html)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>open override fun [cumulativeProbability](cumulative-probability.html)(x0: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), x1: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [density](density.html) | [jvm]<br>open override fun [density](density.html)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getNumericalMean](get-numerical-mean.html) | [jvm]<br>open override fun [getNumericalMean](get-numerical-mean.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getNumericalVariance](get-numerical-variance.html) | [jvm]<br>open override fun [getNumericalVariance](get-numerical-variance.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getSupportLowerBound](get-support-lower-bound.html) | [jvm]<br>open override fun [getSupportLowerBound](get-support-lower-bound.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getSupportUpperBound](get-support-upper-bound.html) | [jvm]<br>open override fun [getSupportUpperBound](get-support-upper-bound.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [inverseCumulativeProbability](inverse-cumulative-probability.html) | [jvm]<br>open override fun [inverseCumulativeProbability](inverse-cumulative-probability.html)(p: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [isSupportConnected](is-support-connected.html) | [jvm]<br>open override fun [isSupportConnected](is-support-connected.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isSupportLowerBoundInclusive](is-support-lower-bound-inclusive.html) | [jvm]<br>open override fun [isSupportLowerBoundInclusive](is-support-lower-bound-inclusive.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isSupportUpperBoundInclusive](is-support-upper-bound-inclusive.html) | [jvm]<br>open override fun [isSupportUpperBoundInclusive](is-support-upper-bound-inclusive.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [probability](probability.html) | [jvm]<br>open override fun [probability](probability.html)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [reseedRandomGenerator](reseed-random-generator.html) | [jvm]<br>open override fun [reseedRandomGenerator](reseed-random-generator.html)(seed: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |
| [sample](sample.html) | [jvm]<br>open override fun [sample](sample.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>open override fun [sample](sample.html)(sampleSize: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html) |


## Properties


| Name | Summary |
|---|---|
| [value](value.html) | [jvm]<br>val [value](value.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |


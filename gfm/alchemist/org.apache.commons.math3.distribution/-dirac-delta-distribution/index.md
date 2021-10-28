//[alchemist](../../../index.md)/[org.apache.commons.math3.distribution](../index.md)/[DiracDeltaDistribution](index.md)

# DiracDeltaDistribution

[jvm]\
class [DiracDeltaDistribution](index.md)(**value**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : RealDistribution, [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Models a Real Distribution backed by a Dirac Delta Function. This is similar to a Logistic probability function with a shape whose value tends to zero.

In practice, samples from this function return the provided [value](value.md) as a constant. The variance is zero, there is no randomness involved, and most of the useful information of a real distribution are actually lost. However, this utility can transform tools meant to work with a probability function in such a way that they work with a constant value (e.g., random walks with a constant step).

## Constructors

| | |
|---|---|
| [DiracDeltaDistribution](-dirac-delta-distribution.md) | [jvm]<br>fun [DiracDeltaDistribution](-dirac-delta-distribution.md)(randomGenerator: RandomGenerator? = null, value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>This constructor is meant for reflection compatibility only. |
| [DiracDeltaDistribution](-dirac-delta-distribution.md) | [jvm]<br>fun [DiracDeltaDistribution](-dirac-delta-distribution.md)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |

## Functions

| Name | Summary |
|---|---|
| [cumulativeProbability](cumulative-probability.md) | [jvm]<br>open override fun [cumulativeProbability](cumulative-probability.md)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>open override fun [cumulativeProbability](cumulative-probability.md)(x0: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), x1: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [density](density.md) | [jvm]<br>open override fun [density](density.md)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getNumericalMean](get-numerical-mean.md) | [jvm]<br>open override fun [getNumericalMean](get-numerical-mean.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getNumericalVariance](get-numerical-variance.md) | [jvm]<br>open override fun [getNumericalVariance](get-numerical-variance.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getSupportLowerBound](get-support-lower-bound.md) | [jvm]<br>open override fun [getSupportLowerBound](get-support-lower-bound.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getSupportUpperBound](get-support-upper-bound.md) | [jvm]<br>open override fun [getSupportUpperBound](get-support-upper-bound.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [inverseCumulativeProbability](inverse-cumulative-probability.md) | [jvm]<br>open override fun [inverseCumulativeProbability](inverse-cumulative-probability.md)(p: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [isSupportConnected](is-support-connected.md) | [jvm]<br>open override fun [isSupportConnected](is-support-connected.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isSupportLowerBoundInclusive](is-support-lower-bound-inclusive.md) | [jvm]<br>open override fun [isSupportLowerBoundInclusive](is-support-lower-bound-inclusive.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isSupportUpperBoundInclusive](is-support-upper-bound-inclusive.md) | [jvm]<br>open override fun [isSupportUpperBoundInclusive](is-support-upper-bound-inclusive.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [probability](probability.md) | [jvm]<br>open override fun [probability](probability.md)(x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [reseedRandomGenerator](reseed-random-generator.md) | [jvm]<br>open override fun [reseedRandomGenerator](reseed-random-generator.md)(seed: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |
| [sample](sample.md) | [jvm]<br>open override fun [sample](sample.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>open override fun [sample](sample.md)(sampleSize: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html) |

## Properties

| Name | Summary |
|---|---|
| [value](value.md) | [jvm]<br>val [value](value.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |

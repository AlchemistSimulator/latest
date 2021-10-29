---
title: Time
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Time](index.html)



# Time



[jvm]\
interface [Time](index.html) : [Comparable](https://docs.oracle.com/javase/8/docs/api/java/lang/Comparable.html)<[Time](index.html)> , [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Interface for time representation.



## Functions


| Name | Summary |
|---|---|
| [compareTo](../-g-p-s-point/index.html#-1554281679%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [compareTo](../-g-p-s-point/index.html#-1554281679%2FFunctions%2F-134779887)(p: [T](../../it.unibo.alchemist.core.interfaces/-scheduler/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isInfinite](is-infinite.html) | [jvm]<br>abstract fun [isInfinite](is-infinite.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Verifies if the [Time](index.html) is set at infinite, namely if the event will never happen. |
| [minus](minus.html) | [jvm]<br>abstract fun [minus](minus.html)(dt: [Time](index.html)): [Time](index.html)<br>Allows to subtract a [Time](index.html) to this [Time](index.html). |
| [plus](plus.html) | [jvm]<br>abstract fun [plus](plus.html)(dt: [Time](index.html)): [Time](index.html)<br>Allows to add a [Time](index.html) to this [Time](index.html). |
| [times](times.html) | [jvm]<br>abstract fun [times](times.html)(var: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Time](index.html)<br>Allows to multiply this [Time](index.html) for a constant. |
| [toDouble](to-double.html) | [jvm]<br>abstract fun [toDouble](to-double.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Allows to get a double representation of this [Time](index.html). |


## Properties


| Name | Summary |
|---|---|
| [INFINITY](-i-n-f-i-n-i-t-y.html) | [jvm]<br>val [INFINITY](-i-n-f-i-n-i-t-y.html): [Time](index.html)<br>Indefinitely future time. |
| [ZERO](-z-e-r-o.html) | [jvm]<br>val [ZERO](-z-e-r-o.html): [Time](index.html)<br>Initial time. |


## Inheritors


| Name |
|---|
| [DoubleTime](../../it.unibo.alchemist.model.implementations.times/-double-time/index.html) |


## Extensions


| Name | Summary |
|---|---|
| [minus](../../it.unibo.alchemist.model/minus.html) | [jvm]<br>operator fun [Time](index.html).[minus](../../it.unibo.alchemist.model/minus.html)(other: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Time](index.html)<br>Minus operator for [Time](index.html) and [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html). |
| [plus](../../it.unibo.alchemist.model/plus.html) | [jvm]<br>operator fun [Time](index.html).[plus](../../it.unibo.alchemist.model/plus.html)(other: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Time](index.html)<br>Plus operator for [Time](index.html) and [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html). |


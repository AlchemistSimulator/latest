//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Time](index.md)

# Time

[jvm]\
interface [Time](index.md) : [Comparable](https://docs.oracle.com/javase/8/docs/api/java/lang/Comparable.html)<[Time](index.md)> , [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Interface for time representation.

## Functions

| Name | Summary |
|---|---|
| [compareTo](../-g-p-s-point/index.md#-1554281679%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [compareTo](../-g-p-s-point/index.md#-1554281679%2FFunctions%2F-267951372)(p: [T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isInfinite](is-infinite.md) | [jvm]<br>abstract fun [isInfinite](is-infinite.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Verifies if the [Time](index.md) is set at infinite, namely if the event will never happen. |
| [minus](minus.md) | [jvm]<br>abstract fun [minus](minus.md)(dt: [Time](index.md)): [Time](index.md)<br>Allows to subtract a [Time](index.md) to this [Time](index.md). |
| [plus](plus.md) | [jvm]<br>abstract fun [plus](plus.md)(dt: [Time](index.md)): [Time](index.md)<br>Allows to add a [Time](index.md) to this [Time](index.md). |
| [times](times.md) | [jvm]<br>abstract fun [times](times.md)(var: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Time](index.md)<br>Allows to multiply this [Time](index.md) for a constant. |
| [toDouble](to-double.md) | [jvm]<br>abstract fun [toDouble](to-double.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Allows to get a double representation of this [Time](index.md). |

## Properties

| Name | Summary |
|---|---|
| [INFINITY](-i-n-f-i-n-i-t-y.md) | [jvm]<br>val [INFINITY](-i-n-f-i-n-i-t-y.md): [Time](index.md)<br>Indefinitely future time. |
| [ZERO](-z-e-r-o.md) | [jvm]<br>val [ZERO](-z-e-r-o.md): [Time](index.md)<br>Initial time. |

## Inheritors

| Name |
|---|
| [DoubleTime](../../it.unibo.alchemist.model.implementations.times/-double-time/index.md) |

## Extensions

| Name | Summary |
|---|---|
| [minus](../../it.unibo.alchemist.model/minus.md) | [jvm]<br>operator fun [Time](index.md).[minus](../../it.unibo.alchemist.model/minus.md)(other: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Time](index.md)<br>Minus operator for [Time](index.md) and [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html). |
| [plus](../../it.unibo.alchemist.model/plus.md) | [jvm]<br>operator fun [Time](index.md).[plus](../../it.unibo.alchemist.model/plus.md)(other: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Time](index.md)<br>Plus operator for [Time](index.md) and [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html). |

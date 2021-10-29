---
title: DoubleTime
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.times](../index.html)/[DoubleTime](index.html)



# DoubleTime



[jvm]\
class [DoubleTime](index.html) : [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)

This class is meant to provide a reasonably fast time implementation. Should be suitable for most usages, but it inherits the problem of the loss of precision of double numbers when comparing big numbers with low numbers. It could become a real problem with long simulations.



## Constructors


| | |
|---|---|
| [DoubleTime](-double-time.html) | [jvm]<br>open fun [DoubleTime](-double-time.html)()<br>Default empty constructor, builds a DoubleTime with value 0. |
| [DoubleTime](-double-time.html) | [jvm]<br>open fun [DoubleTime](-double-time.html)(val: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Builds a new DoubleTime starting from the specified value. |


## Functions


| Name | Summary |
|---|---|
| [compareTo](compare-to.html) | [jvm]<br>open fun [compareTo](compare-to.html)(o: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [equals](equals.html) | [jvm]<br>open fun [equals](equals.html)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hashCode](hash-code.html) | [jvm]<br>open fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isInfinite](is-infinite.html) | [jvm]<br>open fun [isInfinite](is-infinite.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [minus](minus.html) | [jvm]<br>open fun [minus](minus.html)(dt: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html) |
| [plus](plus.html) | [jvm]<br>open fun [plus](plus.html)(dt: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [DoubleTime](index.html) |
| [times](times.html) | [jvm]<br>open fun [times](times.html)(var: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html) |
| [toDouble](to-double.html) | [jvm]<br>open fun [toDouble](to-double.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


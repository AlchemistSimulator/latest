//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.times](../index.md)/[DoubleTime](index.md)

# DoubleTime

[jvm]\
class [DoubleTime](index.md) : [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)

This class is meant to provide a reasonably fast time implementation. Should be suitable for most usages, but it inherits the problem of the loss of precision of double numbers when comparing big numbers with low numbers. It could become a real problem with long simulations.

## Constructors

| | |
|---|---|
| [DoubleTime](-double-time.md) | [jvm]<br>open fun [DoubleTime](-double-time.md)()<br>Default empty constructor, builds a DoubleTime with value 0. |
| [DoubleTime](-double-time.md) | [jvm]<br>open fun [DoubleTime](-double-time.md)(val: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Builds a new DoubleTime starting from the specified value. |

## Functions

| Name | Summary |
|---|---|
| [compareTo](compare-to.md) | [jvm]<br>open fun [compareTo](compare-to.md)(o: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [equals](equals.md) | [jvm]<br>open fun [equals](equals.md)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hashCode](hash-code.md) | [jvm]<br>open fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isInfinite](is-infinite.md) | [jvm]<br>open fun [isInfinite](is-infinite.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [minus](minus.md) | [jvm]<br>open fun [minus](minus.md)(dt: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md) |
| [plus](plus.md) | [jvm]<br>open fun [plus](plus.md)(dt: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [DoubleTime](index.md) |
| [times](times.md) | [jvm]<br>open fun [times](times.md)(var: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md) |
| [toDouble](to-double.md) | [jvm]<br>open fun [toDouble](to-double.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

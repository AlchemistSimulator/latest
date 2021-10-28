//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.export](../index.md)/[FilteringPolicy](index.md)

# FilteringPolicy

[jvm]\
@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()

interface [FilteringPolicy](index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Expresses a flat map operation over a double.

## Functions

| Name | Summary |
|---|---|
| [apply](apply.md) | [jvm]<br>abstract fun [apply](apply.md)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [DoubleStream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/DoubleStream.html)<br>From a single value, builds a stream of values. |

---
title: it.unibo.alchemist.loader.variables
---
//[alchemist](../../index.html)/[it.unibo.alchemist.loader.variables](index.html)



# Package it.unibo.alchemist.loader.variables



## Types


| Name | Summary |
|---|---|
| [ArbitraryVariable](-arbitrary-variable/index.html) | [jvm]<br>class [ArbitraryVariable](-arbitrary-variable/index.html) : [PrintableVariable](-printable-variable/index.html)<[Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)> <br>A variable spanning over an arbitrary set of values. |
| [Constant](-constant/index.html) | [jvm]<br>class [Constant](-constant/index.html)<[V](-constant/index.html)>(**value**: [V](-constant/index.html)) : [DependentVariable](-dependent-variable/index.html)<[V](-constant/index.html)> <br>A constant [value](-constant/value.html), expressed as a variable to promote code reuse in Alchemist specifications. |
| [DependentVariable](-dependent-variable/index.html) | [jvm]<br>@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()<br>interface [DependentVariable](-dependent-variable/index.html)<[V](-dependent-variable/index.html)> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>A dependent variable, namely a variable whose value can be obtained given the values of other variables. |
| [Flag](-flag/index.html) | [jvm]<br>class [Flag](-flag/index.html) : [PrintableVariable](-printable-variable/index.html)<[Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)> <br>This variable is a flag. |
| [GeometricVariable](-geometric-variable/index.html) | [jvm]<br>class [GeometricVariable](-geometric-variable/index.html) : [PrintableVariable](-printable-variable/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> <br>A variable ranging geometrically (exponentially) in a range. |
| [JSR223Variable](-j-s-r223-variable/index.html) | [jvm]<br>data class [JSR223Variable](-j-s-r223-variable/index.html)<[R](-j-s-r223-variable/index.html)>(**language**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **formula**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [DependentVariable](-dependent-variable/index.html)<[R](-j-s-r223-variable/index.html)> <br>This variable loads any [JSR-233](http://archive.fo/PGdk8) language available in the classpath. |
| [LinearVariable](-linear-variable/index.html) | [jvm]<br>class [LinearVariable](-linear-variable/index.html) : [PrintableVariable](-printable-variable/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> <br>This class represents a linear variable, namely a variable whose values span linearly between minimum and maximum. |
| [NumericConstant](-numeric-constant/index.html) | [jvm]<br>class [NumericConstant](-numeric-constant/index.html) : [DependentVariable](-dependent-variable/index.html)<[Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)> <br>A numeric constant. |
| [PrintableVariable](-printable-variable/index.html) | [jvm]<br>abstract class [PrintableVariable](-printable-variable/index.html)<[V](-printable-variable/index.html) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)?> : [Variable](-variable/index.html)<[V](-printable-variable/index.html)> <br>A variable stub, with a default [toString](-printable-variable/to-string.html) method. |
| [Variable](-variable/index.html) | [jvm]<br>interface [Variable](-variable/index.html)<[V](-variable/index.html) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)<[V](-printable-variable/index.html)> <br>A variable simulation value, that provides a range of values for batches, and a default value for single-shot runs. |


---
title: UncomparableDistancesException
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.exceptions](../index.html)/[UncomparableDistancesException](index.html)



# UncomparableDistancesException



[jvm]\
class [UncomparableDistancesException](index.html) : [IllegalArgumentException](https://docs.oracle.com/javase/8/docs/api/java/lang/IllegalArgumentException.html)

An exception meant to be thrown when trying to compare incompatible distances.



## Constructors


| | |
|---|---|
| [UncomparableDistancesException](-uncomparable-distances-exception.html) | [jvm]<br>open fun [UncomparableDistancesException](-uncomparable-distances-exception.html)(pos1: [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, pos2: [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, cause: [Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html))<br>Builds the exception given two positions claimed to be not compatible. |
| [UncomparableDistancesException](-uncomparable-distances-exception.html) | [jvm]<br>open fun [UncomparableDistancesException](-uncomparable-distances-exception.html)(pos1: [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, pos2: [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>Builds the exception given two positions claimed to be not compatible. |


## Functions


| Name | Summary |
|---|---|
| [addSuppressed](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.html#-1898257014%2FFunctions%2F-134779887) | [jvm]<br>fun [addSuppressed](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.html#-1898257014%2FFunctions%2F-134779887)(exception: [Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html)) |
| [fillInStackTrace](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.html#-1207709164%2FFunctions%2F-134779887) | [jvm]<br>open fun [fillInStackTrace](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.html#-1207709164%2FFunctions%2F-134779887)(): [Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html) |
| [getCause](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.html#-252564762%2FFunctions%2F-134779887) | [jvm]<br>open fun [getCause](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.html#-252564762%2FFunctions%2F-134779887)(): [Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html) |
| [getLocalizedMessage](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.html#-2138642817%2FFunctions%2F-134779887) | [jvm]<br>open fun [getLocalizedMessage](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.html#-2138642817%2FFunctions%2F-134779887)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [getMessage](get-message.html) | [jvm]<br>open fun [getMessage](get-message.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [getStackTrace](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.html#-1238049138%2FFunctions%2F-134779887) | [jvm]<br>open fun [getStackTrace](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.html#-1238049138%2FFunctions%2F-134779887)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[StackTraceElement](https://docs.oracle.com/javase/8/docs/api/java/lang/StackTraceElement.html)> |
| [getSuppressed](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.html#1678506999%2FFunctions%2F-134779887) | [jvm]<br>fun [getSuppressed](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.html#1678506999%2FFunctions%2F-134779887)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html)> |
| [initCause](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.html#-104903378%2FFunctions%2F-134779887) | [jvm]<br>open fun [initCause](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.html#-104903378%2FFunctions%2F-134779887)(cause: [Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html)): [Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html) |
| [printStackTrace](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.html#-1357294889%2FFunctions%2F-134779887) | [jvm]<br>open fun [printStackTrace](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.html#-1357294889%2FFunctions%2F-134779887)() |
| [setStackTrace](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.html#-1146009933%2FFunctions%2F-134779887) | [jvm]<br>open fun [setStackTrace](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.html#-1146009933%2FFunctions%2F-134779887)(stackTrace: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[StackTraceElement](https://docs.oracle.com/javase/8/docs/api/java/lang/StackTraceElement.html)>) |
| [toString](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.html#1869833549%2FFunctions%2F-134779887) | [jvm]<br>open fun [toString](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.html#1869833549%2FFunctions%2F-134779887)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


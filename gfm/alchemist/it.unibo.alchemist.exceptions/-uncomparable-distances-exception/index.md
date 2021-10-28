//[alchemist](../../../index.md)/[it.unibo.alchemist.exceptions](../index.md)/[UncomparableDistancesException](index.md)

# UncomparableDistancesException

[jvm]\
class [UncomparableDistancesException](index.md) : [IllegalArgumentException](https://docs.oracle.com/javase/8/docs/api/java/lang/IllegalArgumentException.html)

An exception meant to be thrown when trying to compare incompatible distances.

## Constructors

| | |
|---|---|
| [UncomparableDistancesException](-uncomparable-distances-exception.md) | [jvm]<br>open fun [UncomparableDistancesException](-uncomparable-distances-exception.md)(pos1: [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, pos2: [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, cause: [Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html))<br>Builds the exception given two positions claimed to be not compatible. |
| [UncomparableDistancesException](-uncomparable-distances-exception.md) | [jvm]<br>open fun [UncomparableDistancesException](-uncomparable-distances-exception.md)(pos1: [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, pos2: [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>Builds the exception given two positions claimed to be not compatible. |

## Functions

| Name | Summary |
|---|---|
| [addSuppressed](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.md#-1898257014%2FFunctions%2F-267951372) | [jvm]<br>fun [addSuppressed](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.md#-1898257014%2FFunctions%2F-267951372)(exception: [Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html)) |
| [fillInStackTrace](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.md#-1207709164%2FFunctions%2F-267951372) | [jvm]<br>open fun [fillInStackTrace](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.md#-1207709164%2FFunctions%2F-267951372)(): [Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html) |
| [getCause](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.md#-252564762%2FFunctions%2F-267951372) | [jvm]<br>open fun [getCause](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.md#-252564762%2FFunctions%2F-267951372)(): [Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html) |
| [getLocalizedMessage](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.md#-2138642817%2FFunctions%2F-267951372) | [jvm]<br>open fun [getLocalizedMessage](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.md#-2138642817%2FFunctions%2F-267951372)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [getMessage](get-message.md) | [jvm]<br>open fun [getMessage](get-message.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [getStackTrace](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.md#-1238049138%2FFunctions%2F-267951372) | [jvm]<br>open fun [getStackTrace](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.md#-1238049138%2FFunctions%2F-267951372)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[StackTraceElement](https://docs.oracle.com/javase/8/docs/api/java/lang/StackTraceElement.html)> |
| [getSuppressed](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.md#1678506999%2FFunctions%2F-267951372) | [jvm]<br>fun [getSuppressed](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.md#1678506999%2FFunctions%2F-267951372)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html)> |
| [initCause](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.md#-104903378%2FFunctions%2F-267951372) | [jvm]<br>open fun [initCause](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.md#-104903378%2FFunctions%2F-267951372)(cause: [Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html)): [Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html) |
| [printStackTrace](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.md#-1357294889%2FFunctions%2F-267951372) | [jvm]<br>open fun [printStackTrace](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.md#-1357294889%2FFunctions%2F-267951372)() |
| [setStackTrace](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.md#-1146009933%2FFunctions%2F-267951372) | [jvm]<br>open fun [setStackTrace](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.md#-1146009933%2FFunctions%2F-267951372)(stackTrace: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[StackTraceElement](https://docs.oracle.com/javase/8/docs/api/java/lang/StackTraceElement.html)>) |
| [toString](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.md#1869833549%2FFunctions%2F-267951372) | [jvm]<br>open fun [toString](../../it.unibo.alchemist.expressions.parser/-parse-exception/index.md#1869833549%2FFunctions%2F-267951372)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

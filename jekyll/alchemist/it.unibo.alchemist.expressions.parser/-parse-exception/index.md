---
title: ParseException
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.expressions.parser](../index.html)/[ParseException](index.html)



# ParseException



[jvm]\
open class [ParseException](index.html) : [RuntimeException](https://docs.oracle.com/javase/8/docs/api/java/lang/RuntimeException.html)

This exception is thrown when parse errors are encountered. You can explicitly create objects of this exception type by calling the method generateParseException in the generated parser. You can modify this class to customize your error reporting mechanisms so long as you retain the public fields.



## Constructors


| | |
|---|---|
| [ParseException](-parse-exception.html) | [jvm]<br>open fun [ParseException](-parse-exception.html)(currentTokenVal: [Token](../-token/index.html), expectedTokenSequencesVal: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>>, tokenImageVal: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)>)<br>This constructor is used by the method "generateParseException" in the generated parser. |
| [ParseException](-parse-exception.html) | [jvm]<br>open fun [ParseException](-parse-exception.html)()<br>The following constructors are for use by you for whatever purpose you can think of. |
| [ParseException](-parse-exception.html) | [jvm]<br>open fun [ParseException](-parse-exception.html)(message: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Constructor with message. |


## Functions


| Name | Summary |
|---|---|
| [addSuppressed](index.html#-1898257014%2FFunctions%2F-134779887) | [jvm]<br>fun [addSuppressed](index.html#-1898257014%2FFunctions%2F-134779887)(exception: [Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html)) |
| [fillInStackTrace](index.html#-1207709164%2FFunctions%2F-134779887) | [jvm]<br>open fun [fillInStackTrace](index.html#-1207709164%2FFunctions%2F-134779887)(): [Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html) |
| [getCause](index.html#-252564762%2FFunctions%2F-134779887) | [jvm]<br>open fun [getCause](index.html#-252564762%2FFunctions%2F-134779887)(): [Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html) |
| [getLocalizedMessage](index.html#-2138642817%2FFunctions%2F-134779887) | [jvm]<br>open fun [getLocalizedMessage](index.html#-2138642817%2FFunctions%2F-134779887)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [getMessage](index.html#1068546184%2FFunctions%2F-134779887) | [jvm]<br>open fun [getMessage](index.html#1068546184%2FFunctions%2F-134779887)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [getStackTrace](index.html#-1238049138%2FFunctions%2F-134779887) | [jvm]<br>open fun [getStackTrace](index.html#-1238049138%2FFunctions%2F-134779887)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[StackTraceElement](https://docs.oracle.com/javase/8/docs/api/java/lang/StackTraceElement.html)> |
| [getSuppressed](index.html#1678506999%2FFunctions%2F-134779887) | [jvm]<br>fun [getSuppressed](index.html#1678506999%2FFunctions%2F-134779887)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html)> |
| [initCause](index.html#-104903378%2FFunctions%2F-134779887) | [jvm]<br>open fun [initCause](index.html#-104903378%2FFunctions%2F-134779887)(cause: [Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html)): [Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html) |
| [printStackTrace](index.html#-1357294889%2FFunctions%2F-134779887) | [jvm]<br>open fun [printStackTrace](index.html#-1357294889%2FFunctions%2F-134779887)() |
| [setStackTrace](index.html#-1146009933%2FFunctions%2F-134779887) | [jvm]<br>open fun [setStackTrace](index.html#-1146009933%2FFunctions%2F-134779887)(stackTrace: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[StackTraceElement](https://docs.oracle.com/javase/8/docs/api/java/lang/StackTraceElement.html)>) |
| [toString](index.html#1869833549%2FFunctions%2F-134779887) | [jvm]<br>open fun [toString](index.html#1869833549%2FFunctions%2F-134779887)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Properties


| Name | Summary |
|---|---|
| [currentToken](current-token.html) | [jvm]<br>open val [currentToken](current-token.html): [Token](../-token/index.html)<br>This is the last token that has been consumed successfully. |
| [expectedTokenSequences](expected-token-sequences.html) | [jvm]<br>open val [expectedTokenSequences](expected-token-sequences.html): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>><br>Each entry in this array is an array of integers. |
| [tokenImage](token-image.html) | [jvm]<br>open val [tokenImage](token-image.html): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)><br>This is a reference to the "tokenImage" array of the generated parser within which the parse error occurred. |


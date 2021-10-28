//[alchemist](../../../index.md)/[it.unibo.alchemist.expressions.parser](../index.md)/[ParseException](index.md)

# ParseException

[jvm]\
open class [ParseException](index.md) : [RuntimeException](https://docs.oracle.com/javase/8/docs/api/java/lang/RuntimeException.html)

This exception is thrown when parse errors are encountered. You can explicitly create objects of this exception type by calling the method generateParseException in the generated parser. You can modify this class to customize your error reporting mechanisms so long as you retain the public fields.

## Constructors

| | |
|---|---|
| [ParseException](-parse-exception.md) | [jvm]<br>open fun [ParseException](-parse-exception.md)(currentTokenVal: [Token](../-token/index.md), expectedTokenSequencesVal: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>>, tokenImageVal: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)>)<br>This constructor is used by the method "generateParseException" in the generated parser. |
| [ParseException](-parse-exception.md) | [jvm]<br>open fun [ParseException](-parse-exception.md)()<br>The following constructors are for use by you for whatever purpose you can think of. |
| [ParseException](-parse-exception.md) | [jvm]<br>open fun [ParseException](-parse-exception.md)(message: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Constructor with message. |

## Functions

| Name | Summary |
|---|---|
| [addSuppressed](index.md#-1898257014%2FFunctions%2F-267951372) | [jvm]<br>fun [addSuppressed](index.md#-1898257014%2FFunctions%2F-267951372)(exception: [Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html)) |
| [fillInStackTrace](index.md#-1207709164%2FFunctions%2F-267951372) | [jvm]<br>open fun [fillInStackTrace](index.md#-1207709164%2FFunctions%2F-267951372)(): [Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html) |
| [getCause](index.md#-252564762%2FFunctions%2F-267951372) | [jvm]<br>open fun [getCause](index.md#-252564762%2FFunctions%2F-267951372)(): [Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html) |
| [getLocalizedMessage](index.md#-2138642817%2FFunctions%2F-267951372) | [jvm]<br>open fun [getLocalizedMessage](index.md#-2138642817%2FFunctions%2F-267951372)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [getMessage](index.md#1068546184%2FFunctions%2F-267951372) | [jvm]<br>open fun [getMessage](index.md#1068546184%2FFunctions%2F-267951372)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [getStackTrace](index.md#-1238049138%2FFunctions%2F-267951372) | [jvm]<br>open fun [getStackTrace](index.md#-1238049138%2FFunctions%2F-267951372)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[StackTraceElement](https://docs.oracle.com/javase/8/docs/api/java/lang/StackTraceElement.html)> |
| [getSuppressed](index.md#1678506999%2FFunctions%2F-267951372) | [jvm]<br>fun [getSuppressed](index.md#1678506999%2FFunctions%2F-267951372)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html)> |
| [initCause](index.md#-104903378%2FFunctions%2F-267951372) | [jvm]<br>open fun [initCause](index.md#-104903378%2FFunctions%2F-267951372)(cause: [Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html)): [Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html) |
| [printStackTrace](index.md#-1357294889%2FFunctions%2F-267951372) | [jvm]<br>open fun [printStackTrace](index.md#-1357294889%2FFunctions%2F-267951372)() |
| [setStackTrace](index.md#-1146009933%2FFunctions%2F-267951372) | [jvm]<br>open fun [setStackTrace](index.md#-1146009933%2FFunctions%2F-267951372)(stackTrace: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[StackTraceElement](https://docs.oracle.com/javase/8/docs/api/java/lang/StackTraceElement.html)>) |
| [toString](index.md#1869833549%2FFunctions%2F-267951372) | [jvm]<br>open fun [toString](index.md#1869833549%2FFunctions%2F-267951372)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

## Properties

| Name | Summary |
|---|---|
| [currentToken](current-token.md) | [jvm]<br>open val [currentToken](current-token.md): [Token](../-token/index.md)<br>This is the last token that has been consumed successfully. |
| [expectedTokenSequences](expected-token-sequences.md) | [jvm]<br>open val [expectedTokenSequences](expected-token-sequences.md): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>><br>Each entry in this array is an array of integers. |
| [tokenImage](token-image.md) | [jvm]<br>open val [tokenImage](token-image.md): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)><br>This is a reference to the "tokenImage" array of the generated parser within which the parse error occurred. |

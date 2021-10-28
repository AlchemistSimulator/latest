//[alchemist](../../../index.md)/[it.unibo.alchemist.expressions.parser](../index.md)/[TokenMgrError](index.md)

# TokenMgrError

[jvm]\
open class [TokenMgrError](index.md) : [Error](https://docs.oracle.com/javase/8/docs/api/java/lang/Error.html)

Token Manager Error.

## Constructors

| | |
|---|---|
| [TokenMgrError](-token-mgr-error.md) | [jvm]<br>open fun [TokenMgrError](-token-mgr-error.md)()<br>No arg constructor. |
| [TokenMgrError](-token-mgr-error.md) | [jvm]<br>open fun [TokenMgrError](-token-mgr-error.md)(message: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), reason: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Constructor with message and reason. |
| [TokenMgrError](-token-mgr-error.md) | [jvm]<br>open fun [TokenMgrError](-token-mgr-error.md)(EOFSeen: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), lexState: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), errorLine: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), errorColumn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), errorAfter: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), curChar: [Char](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char/index.html), reason: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Full Constructor. |

## Functions

| Name | Summary |
|---|---|
| [addSuppressed](../-parse-exception/index.md#-1898257014%2FFunctions%2F-267951372) | [jvm]<br>fun [addSuppressed](../-parse-exception/index.md#-1898257014%2FFunctions%2F-267951372)(exception: [Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html)) |
| [fillInStackTrace](../-parse-exception/index.md#-1207709164%2FFunctions%2F-267951372) | [jvm]<br>open fun [fillInStackTrace](../-parse-exception/index.md#-1207709164%2FFunctions%2F-267951372)(): [Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html) |
| [getCause](../-parse-exception/index.md#-252564762%2FFunctions%2F-267951372) | [jvm]<br>open fun [getCause](../-parse-exception/index.md#-252564762%2FFunctions%2F-267951372)(): [Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html) |
| [getLocalizedMessage](../-parse-exception/index.md#-2138642817%2FFunctions%2F-267951372) | [jvm]<br>open fun [getLocalizedMessage](../-parse-exception/index.md#-2138642817%2FFunctions%2F-267951372)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [getMessage](get-message.md) | [jvm]<br>open fun [getMessage](get-message.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>You can also modify the body of this method to customize your error messages. |
| [getStackTrace](../-parse-exception/index.md#-1238049138%2FFunctions%2F-267951372) | [jvm]<br>open fun [getStackTrace](../-parse-exception/index.md#-1238049138%2FFunctions%2F-267951372)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[StackTraceElement](https://docs.oracle.com/javase/8/docs/api/java/lang/StackTraceElement.html)> |
| [getSuppressed](../-parse-exception/index.md#1678506999%2FFunctions%2F-267951372) | [jvm]<br>fun [getSuppressed](../-parse-exception/index.md#1678506999%2FFunctions%2F-267951372)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html)> |
| [initCause](../-parse-exception/index.md#-104903378%2FFunctions%2F-267951372) | [jvm]<br>open fun [initCause](../-parse-exception/index.md#-104903378%2FFunctions%2F-267951372)(cause: [Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html)): [Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html) |
| [printStackTrace](../-parse-exception/index.md#-1357294889%2FFunctions%2F-267951372) | [jvm]<br>open fun [printStackTrace](../-parse-exception/index.md#-1357294889%2FFunctions%2F-267951372)() |
| [setStackTrace](../-parse-exception/index.md#-1146009933%2FFunctions%2F-267951372) | [jvm]<br>open fun [setStackTrace](../-parse-exception/index.md#-1146009933%2FFunctions%2F-267951372)(stackTrace: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[StackTraceElement](https://docs.oracle.com/javase/8/docs/api/java/lang/StackTraceElement.html)>) |
| [toString](../-parse-exception/index.md#1869833549%2FFunctions%2F-267951372) | [jvm]<br>open fun [toString](../-parse-exception/index.md#1869833549%2FFunctions%2F-267951372)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

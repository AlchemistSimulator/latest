---
title: Token
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.expressions.parser](../index.html)/[Token](index.html)



# Token



[jvm]\
open class [Token](index.html) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Describes the input token stream.



## Constructors


| | |
|---|---|
| [Token](-token.html) | [jvm]<br>open fun [Token](-token.html)()<br>No-argument constructor |
| [Token](-token.html) | [jvm]<br>open fun [Token](-token.html)(kind: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Constructs a new token for the specified Image. |
| [Token](-token.html) | [jvm]<br>open fun [Token](-token.html)(kind: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), image: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Constructs a new token for the specified Image and Kind. |


## Functions


| Name | Summary |
|---|---|
| [getValue](get-value.html) | [jvm]<br>open fun [getValue](get-value.html)(): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)<br>An optional attribute value of the Token. |
| [newToken](new-token.html) | [jvm]<br>open fun [newToken](new-token.html)(ofKind: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Token](index.html)<br>[jvm]<br>open fun [newToken](new-token.html)(ofKind: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), image: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Token](index.html)<br>Returns a new Token object, by default. |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Returns the image. |


## Properties


| Name | Summary |
|---|---|
| [beginColumn](begin-column.html) | [jvm]<br>open val [beginColumn](begin-column.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The column number of the first character of this Token. |
| [beginLine](begin-line.html) | [jvm]<br>open val [beginLine](begin-line.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The line number of the first character of this Token. |
| [endColumn](end-column.html) | [jvm]<br>open val [endColumn](end-column.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The column number of the last character of this Token. |
| [endLine](end-line.html) | [jvm]<br>open val [endLine](end-line.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The line number of the last character of this Token. |
| [image](image.html) | [jvm]<br>open val [image](image.html): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>The string image of the token. |
| [kind](kind.html) | [jvm]<br>open val [kind](kind.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>An integer that describes the kind of this token. |
| [next](next.html) | [jvm]<br>open val [next](next.html): [Token](index.html)<br>A reference to the next regular (non-special) token from the input stream. |
| [specialToken](special-token.html) | [jvm]<br>open val [specialToken](special-token.html): [Token](index.html)<br>This field is used to access special tokens that occur prior to this token, but after the immediately preceding regular (non-special) token. |


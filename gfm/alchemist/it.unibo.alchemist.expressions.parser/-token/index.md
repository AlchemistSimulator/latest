//[alchemist](../../../index.md)/[it.unibo.alchemist.expressions.parser](../index.md)/[Token](index.md)

# Token

[jvm]\
open class [Token](index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Describes the input token stream.

## Constructors

| | |
|---|---|
| [Token](-token.md) | [jvm]<br>open fun [Token](-token.md)()<br>No-argument constructor |
| [Token](-token.md) | [jvm]<br>open fun [Token](-token.md)(kind: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Constructs a new token for the specified Image. |
| [Token](-token.md) | [jvm]<br>open fun [Token](-token.md)(kind: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), image: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Constructs a new token for the specified Image and Kind. |

## Functions

| Name | Summary |
|---|---|
| [getValue](get-value.md) | [jvm]<br>open fun [getValue](get-value.md)(): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)<br>An optional attribute value of the Token. |
| [newToken](new-token.md) | [jvm]<br>open fun [newToken](new-token.md)(ofKind: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Token](index.md)<br>[jvm]<br>open fun [newToken](new-token.md)(ofKind: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), image: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Token](index.md)<br>Returns a new Token object, by default. |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Returns the image. |

## Properties

| Name | Summary |
|---|---|
| [beginColumn](begin-column.md) | [jvm]<br>open val [beginColumn](begin-column.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The column number of the first character of this Token. |
| [beginLine](begin-line.md) | [jvm]<br>open val [beginLine](begin-line.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The line number of the first character of this Token. |
| [endColumn](end-column.md) | [jvm]<br>open val [endColumn](end-column.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The column number of the last character of this Token. |
| [endLine](end-line.md) | [jvm]<br>open val [endLine](end-line.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The line number of the last character of this Token. |
| [image](image.md) | [jvm]<br>open val [image](image.md): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>The string image of the token. |
| [kind](kind.md) | [jvm]<br>open val [kind](kind.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>An integer that describes the kind of this token. |
| [next](next.md) | [jvm]<br>open val [next](next.md): [Token](index.md)<br>A reference to the next regular (non-special) token from the input stream. |
| [specialToken](special-token.md) | [jvm]<br>open val [specialToken](special-token.md): [Token](index.md)<br>This field is used to access special tokens that occur prior to this token, but after the immediately preceding regular (non-special) token. |

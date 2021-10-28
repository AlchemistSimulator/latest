//[alchemist](../../../index.md)/[it.unibo.alchemist.expressions.parser](../index.md)/[Token](index.md)/[getValue](get-value.md)

# getValue

[jvm]\
open fun [getValue](get-value.md)(): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)

An optional attribute value of the Token. Tokens which are not used as syntactic sugar will often contain meaningful values that will be used later on by the compiler or interpreter. This attribute value is often different from the image. Any subclass of Token that actually wants to return a non-null value can override this method as appropriate.

---
title: getValue
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.expressions.parser](../index.html)/[Token](index.html)/[getValue](get-value.html)



# getValue



[jvm]\
open fun [getValue](get-value.html)(): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)



An optional attribute value of the Token. Tokens which are not used as syntactic sugar will often contain meaningful values that will be used later on by the compiler or interpreter. This attribute value is often different from the image. Any subclass of Token that actually wants to return a non-null value can override this method as appropriate.





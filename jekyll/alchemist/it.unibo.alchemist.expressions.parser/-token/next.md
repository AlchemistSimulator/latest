---
title: next
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.expressions.parser](../index.html)/[Token](index.html)/[next](next.html)



# next



[jvm]\
open val [next](next.html): [Token](index.html)



A reference to the next regular (non-special) token from the input stream. If this is the last token from the input stream, or if the token manager has not read tokens beyond this one, this field is set to null. This is true only if this token is also a regular token. Otherwise, see below for a description of the contents of this field.





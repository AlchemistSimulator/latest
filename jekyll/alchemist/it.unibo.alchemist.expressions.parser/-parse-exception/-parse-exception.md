---
title: ParseException
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.expressions.parser](../index.html)/[ParseException](index.html)/[ParseException](-parse-exception.html)



# ParseException



[jvm]\
open fun [ParseException](-parse-exception.html)(currentTokenVal: [Token](../-token/index.html), expectedTokenSequencesVal: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>>, tokenImageVal: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)>)



This constructor is used by the method "generateParseException" in the generated parser. Calling this constructor generates a new object of this type with the fields "currentToken", "expectedTokenSequences", and "tokenImage" set.





[jvm]\
open fun [ParseException](-parse-exception.html)()



The following constructors are for use by you for whatever purpose you can think of. Constructing the exception in this manner makes the exception behave in the normal way - i.e., as documented in the class "Throwable". The fields "errorToken", "expectedTokenSequences", and "tokenImage" do not contain relevant information. The JavaCC generated code does not use these constructors.





[jvm]\
open fun [ParseException](-parse-exception.html)(message: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))



Constructor with message.





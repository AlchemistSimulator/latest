---
title: getMessage
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.expressions.parser](../index.html)/[TokenMgrError](index.html)/[getMessage](get-message.html)



# getMessage



[jvm]\
open fun [getMessage](get-message.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)



You can also modify the body of this method to customize your error messages. For example, cases like LOOP_DETECTED and INVALID_LEXICAL_STATE are not of end-users concern, so you can return something like : "Internal Error : Please file a bug report .... " from this method for such cases in the release version of your parser.





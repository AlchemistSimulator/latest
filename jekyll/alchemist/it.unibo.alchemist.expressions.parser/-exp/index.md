---
title: Exp
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.expressions.parser](../index.html)/[Exp](index.html)



# Exp



[jvm]\
open class [Exp](index.html) : [ExpConstants](../-exp-constants/index.html)



## Constructors


| | |
|---|---|
| [Exp](-exp.html) | [jvm]<br>open fun [Exp](-exp.html)(tm: [ExpTokenManager](../-exp-token-manager/index.html))<br>Constructor with generated Token Manager. |
| [Exp](-exp.html) | [jvm]<br>open fun [Exp](-exp.html)(stream: [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html))<br>Constructor with InputStream. |
| [Exp](-exp.html) | [jvm]<br>open fun [Exp](-exp.html)(stream: [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html), encoding: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Constructor with InputStream and supplied encoding |
| [Exp](-exp.html) | [jvm]<br>open fun [Exp](-exp.html)(stream: [Reader](https://docs.oracle.com/javase/8/docs/api/java/io/Reader.html))<br>Constructor. |


## Functions


| Name | Summary |
|---|---|
| [AtomicExpr](-atomic-expr.html) | [jvm]<br>fun [AtomicExpr](-atomic-expr.html)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [Comparator](-comparator.html) | [jvm]<br>fun [Comparator](-comparator.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [Cost](-cost.html) | [jvm]<br>fun [Cost](-cost.html)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<HashString> |
| [disable_tracing](disable_tracing.html) | [jvm]<br>fun [disable_tracing](disable_tracing.html)()<br>Disable tracing. |
| [E](-e.html) | [jvm]<br>fun [E](-e.html)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [enable_tracing](enable_tracing.html) | [jvm]<br>fun [enable_tracing](enable_tracing.html)()<br>Enable tracing. |
| [Expr](-expr.html) | [jvm]<br>fun [Expr](-expr.html)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [generateParseException](generate-parse-exception.html) | [jvm]<br>open fun [generateParseException](generate-parse-exception.html)(): [ParseException](../-parse-exception/index.html)<br>Generate ParseException. |
| [getNextToken](get-next-token.html) | [jvm]<br>fun [getNextToken](get-next-token.html)(): [Token](../-token/index.html)<br>Get the next Token. |
| [Init](-init.html) | [jvm]<br>fun [Init](-init.html)(): [ITree](../../it.unibo.alchemist.expressions.interfaces/-i-tree/index.html) |
| [listComparator](list-comparator.html) | [jvm]<br>fun [listComparator](list-comparator.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [ListExpr](-list-expr.html) | [jvm]<br>fun [ListExpr](-list-expr.html)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<[Set](https://docs.oracle.com/javase/8/docs/api/java/util/Set.html)<[ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>> |
| [MaxExpr](-max-expr.html) | [jvm]<br>fun [MaxExpr](-max-expr.html)(): [OperatorTreeNode](../../it.unibo.alchemist.expressions.implementations/-operator-tree-node/index.html) |
| [MinExpr](-min-expr.html) | [jvm]<br>fun [MinExpr](-min-expr.html)(): [OperatorTreeNode](../../it.unibo.alchemist.expressions.implementations/-operator-tree-node/index.html) |
| [ModExpr](-mod-expr.html) | [jvm]<br>fun [ModExpr](-mod-expr.html)(): [OperatorTreeNode](../../it.unibo.alchemist.expressions.implementations/-operator-tree-node/index.html) |
| [Number](-number.html) | [jvm]<br>fun [Number](-number.html)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> |
| [ReInit](-re-init.html) | [jvm]<br>open fun [ReInit](-re-init.html)(tm: [ExpTokenManager](../-exp-token-manager/index.html))<br>open fun [ReInit](-re-init.html)(stream: [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html))<br>open fun [ReInit](-re-init.html)(stream: [Reader](https://docs.oracle.com/javase/8/docs/api/java/io/Reader.html))<br>open fun [ReInit](-re-init.html)(stream: [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html), encoding: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Reinitialise. |
| [TimesExpr](-times-expr.html) | [jvm]<br>fun [TimesExpr](-times-expr.html)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [unaryListComparator](unary-list-comparator.html) | [jvm]<br>fun [unaryListComparator](unary-list-comparator.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [Var](-var.html) | [jvm]<br>fun [Var](-var.html)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |


## Properties


| Name | Summary |
|---|---|
| [jj_nt](jj_nt.html) | [jvm]<br>open val [jj_nt](jj_nt.html): [Token](../-token/index.html)<br>Next token. |
| [token](token.html) | [jvm]<br>open var [token](token.html): [Token](../-token/index.html)<br>Current token. |
| [token_source](token_source.html) | [jvm]<br>open val [token_source](token_source.html): [ExpTokenManager](../-exp-token-manager/index.html)<br>Generated Token Manager. |


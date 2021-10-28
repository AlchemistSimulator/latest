//[alchemist](../../../index.md)/[it.unibo.alchemist.expressions.parser](../index.md)/[Exp](index.md)

# Exp

[jvm]\
open class [Exp](index.md) : [ExpConstants](../-exp-constants/index.md)

## Constructors

| | |
|---|---|
| [Exp](-exp.md) | [jvm]<br>open fun [Exp](-exp.md)(tm: [ExpTokenManager](../-exp-token-manager/index.md))<br>Constructor with generated Token Manager. |
| [Exp](-exp.md) | [jvm]<br>open fun [Exp](-exp.md)(stream: [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html))<br>Constructor with InputStream. |
| [Exp](-exp.md) | [jvm]<br>open fun [Exp](-exp.md)(stream: [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html), encoding: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Constructor with InputStream and supplied encoding |
| [Exp](-exp.md) | [jvm]<br>open fun [Exp](-exp.md)(stream: [Reader](https://docs.oracle.com/javase/8/docs/api/java/io/Reader.html))<br>Constructor. |

## Functions

| Name | Summary |
|---|---|
| [AtomicExpr](-atomic-expr.md) | [jvm]<br>fun [AtomicExpr](-atomic-expr.md)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [Comparator](-comparator.md) | [jvm]<br>fun [Comparator](-comparator.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [Cost](-cost.md) | [jvm]<br>fun [Cost](-cost.md)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<HashString> |
| [disable_tracing](disable_tracing.md) | [jvm]<br>fun [disable_tracing](disable_tracing.md)()<br>Disable tracing. |
| [E](-e.md) | [jvm]<br>fun [E](-e.md)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [enable_tracing](enable_tracing.md) | [jvm]<br>fun [enable_tracing](enable_tracing.md)()<br>Enable tracing. |
| [Expr](-expr.md) | [jvm]<br>fun [Expr](-expr.md)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [generateParseException](generate-parse-exception.md) | [jvm]<br>open fun [generateParseException](generate-parse-exception.md)(): [ParseException](../-parse-exception/index.md)<br>Generate ParseException. |
| [getNextToken](get-next-token.md) | [jvm]<br>fun [getNextToken](get-next-token.md)(): [Token](../-token/index.md)<br>Get the next Token. |
| [Init](-init.md) | [jvm]<br>fun [Init](-init.md)(): [ITree](../../it.unibo.alchemist.expressions.interfaces/-i-tree/index.md) |
| [listComparator](list-comparator.md) | [jvm]<br>fun [listComparator](list-comparator.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [ListExpr](-list-expr.md) | [jvm]<br>fun [ListExpr](-list-expr.md)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<[Set](https://docs.oracle.com/javase/8/docs/api/java/util/Set.html)<[ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>> |
| [MaxExpr](-max-expr.md) | [jvm]<br>fun [MaxExpr](-max-expr.md)(): [OperatorTreeNode](../../it.unibo.alchemist.expressions.implementations/-operator-tree-node/index.md) |
| [MinExpr](-min-expr.md) | [jvm]<br>fun [MinExpr](-min-expr.md)(): [OperatorTreeNode](../../it.unibo.alchemist.expressions.implementations/-operator-tree-node/index.md) |
| [ModExpr](-mod-expr.md) | [jvm]<br>fun [ModExpr](-mod-expr.md)(): [OperatorTreeNode](../../it.unibo.alchemist.expressions.implementations/-operator-tree-node/index.md) |
| [Number](-number.md) | [jvm]<br>fun [Number](-number.md)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> |
| [ReInit](-re-init.md) | [jvm]<br>open fun [ReInit](-re-init.md)(tm: [ExpTokenManager](../-exp-token-manager/index.md))<br>open fun [ReInit](-re-init.md)(stream: [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html))<br>open fun [ReInit](-re-init.md)(stream: [Reader](https://docs.oracle.com/javase/8/docs/api/java/io/Reader.html))<br>open fun [ReInit](-re-init.md)(stream: [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html), encoding: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Reinitialise. |
| [TimesExpr](-times-expr.md) | [jvm]<br>fun [TimesExpr](-times-expr.md)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [unaryListComparator](unary-list-comparator.md) | [jvm]<br>fun [unaryListComparator](unary-list-comparator.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [Var](-var.md) | [jvm]<br>fun [Var](-var.md)(): [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |

## Properties

| Name | Summary |
|---|---|
| [jj_nt](jj_nt.md) | [jvm]<br>open val [jj_nt](jj_nt.md): [Token](../-token/index.md)<br>Next token. |
| [token](token.md) | [jvm]<br>open var [token](token.md): [Token](../-token/index.md)<br>Current token. |
| [token_source](token_source.md) | [jvm]<br>open val [token_source](token_source.md): [ExpTokenManager](../-exp-token-manager/index.md)<br>Generated Token Manager. |

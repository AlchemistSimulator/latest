---
title: DecimalContext
---
//[alchemist](../../../../index.html)/[it.unibo.alchemist.biochemistrydsl](../../index.html)/[BiochemistrydslParser](../index.html)/[DecimalContext](index.html)



# DecimalContext



[jvm]\
open class [DecimalContext](index.html) : ParserRuleContext



## Constructors


| | |
|---|---|
| [DecimalContext](-decimal-context.html) | [jvm]<br>open fun [DecimalContext](-decimal-context.html)(parent: ParserRuleContext, invokingState: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |


## Functions


| Name | Summary |
|---|---|
| [accept](accept.html) | [jvm]<br>open fun <[T](accept.html)> [accept](accept.html)(visitor: ParseTreeVisitor<out [T](../../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html)>): [T](../../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html) |
| [addAnyChild](index.html#1230525611%2FFunctions%2F-134779887) | [jvm]<br>open fun <[T](index.html#1230525611%2FFunctions%2F-134779887) : ParseTree?> [addAnyChild](index.html#1230525611%2FFunctions%2F-134779887)(t: [T](../../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html)): [T](../../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html) |
| [addChild](index.html#1788416147%2FFunctions%2F-134779887) | [jvm]<br>open fun [addChild](index.html#1788416147%2FFunctions%2F-134779887)(ruleInvocation: RuleContext): RuleContext<br>open fun [addChild](index.html#1159546456%2FFunctions%2F-134779887)(t: TerminalNode): TerminalNode |
| [addErrorNode](index.html#92209968%2FFunctions%2F-134779887) | [jvm]<br>open fun [addErrorNode](index.html#92209968%2FFunctions%2F-134779887)(errorNode: ErrorNode): ErrorNode |
| [copyFrom](index.html#-946529010%2FFunctions%2F-134779887) | [jvm]<br>open fun [copyFrom](index.html#-946529010%2FFunctions%2F-134779887)(ctx: ParserRuleContext) |
| [depth](index.html#333925234%2FFunctions%2F-134779887) | [jvm]<br>open fun [depth](index.html#333925234%2FFunctions%2F-134779887)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [enterRule](enter-rule.html) | [jvm]<br>open fun [enterRule](enter-rule.html)(listener: ParseTreeListener) |
| [exitRule](exit-rule.html) | [jvm]<br>open fun [exitRule](exit-rule.html)(listener: ParseTreeListener) |
| [getAltNumber](index.html#-1572319351%2FFunctions%2F-134779887) | [jvm]<br>open fun [getAltNumber](index.html#-1572319351%2FFunctions%2F-134779887)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getChild](index.html#1085819703%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getChild](index.html#1085819703%2FFunctions%2F-134779887)(p: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): Tree<br>open fun [getChild](index.html#1723621075%2FFunctions%2F-134779887)(i: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): ParseTree<br>open fun <[T](index.html#938276746%2FFunctions%2F-134779887) : ParseTree?> [getChild](index.html#938276746%2FFunctions%2F-134779887)(ctxType: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<out [T](../../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html)>, i: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [T](../../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html) |
| [getChildCount](index.html#571734315%2FFunctions%2F-134779887) | [jvm]<br>open fun [getChildCount](index.html#571734315%2FFunctions%2F-134779887)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getParent](index.html#1944277201%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getParent](index.html#1944277201%2FFunctions%2F-134779887)(): ParseTree<br>abstract fun [getParent](index.html#-1040426088%2FFunctions%2F-134779887)(): Tree<br>open fun [getParent](index.html#837330484%2FFunctions%2F-134779887)(): ParserRuleContext<br>open fun [getParent](index.html#1907908917%2FFunctions%2F-134779887)(): RuleContext |
| [getPayload](index.html#-1797056182%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getPayload](index.html#-1797056182%2FFunctions%2F-134779887)(): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)<br>open fun [getPayload](index.html#-592984243%2FFunctions%2F-134779887)(): RuleContext |
| [getRuleContext](index.html#-2113309080%2FFunctions%2F-134779887) | [jvm]<br>open fun [getRuleContext](index.html#-2113309080%2FFunctions%2F-134779887)(): RuleContext<br>open fun <[T](index.html#1994260019%2FFunctions%2F-134779887) : ParserRuleContext?> [getRuleContext](index.html#1994260019%2FFunctions%2F-134779887)(ctxType: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<out [T](../../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html)>, i: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [T](../../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html) |
| [getRuleContexts](index.html#-2110034828%2FFunctions%2F-134779887) | [jvm]<br>open fun <[T](index.html#-2110034828%2FFunctions%2F-134779887) : ParserRuleContext?> [getRuleContexts](index.html#-2110034828%2FFunctions%2F-134779887)(ctxType: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<out [T](../../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html)>): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[T](../../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html)> |
| [getRuleIndex](get-rule-index.html) | [jvm]<br>open fun [getRuleIndex](get-rule-index.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getSourceInterval](index.html#-548641634%2FFunctions%2F-134779887) | [jvm]<br>open fun [getSourceInterval](index.html#-548641634%2FFunctions%2F-134779887)(): Interval |
| [getStart](index.html#408312218%2FFunctions%2F-134779887) | [jvm]<br>open fun [getStart](index.html#408312218%2FFunctions%2F-134779887)(): Token |
| [getStop](index.html#1724227100%2FFunctions%2F-134779887) | [jvm]<br>open fun [getStop](index.html#1724227100%2FFunctions%2F-134779887)(): Token |
| [getText](index.html#568950418%2FFunctions%2F-134779887) | [jvm]<br>open fun [getText](index.html#568950418%2FFunctions%2F-134779887)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [getToken](index.html#-2011859900%2FFunctions%2F-134779887) | [jvm]<br>open fun [getToken](index.html#-2011859900%2FFunctions%2F-134779887)(ttype: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), i: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): TerminalNode |
| [getTokens](index.html#1407783727%2FFunctions%2F-134779887) | [jvm]<br>open fun [getTokens](index.html#1407783727%2FFunctions%2F-134779887)(ttype: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<TerminalNode> |
| [isEmpty](index.html#-1122734606%2FFunctions%2F-134779887) | [jvm]<br>open fun [isEmpty](index.html#-1122734606%2FFunctions%2F-134779887)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [POSDOUBLE](-p-o-s-d-o-u-b-l-e.html) | [jvm]<br>open fun [POSDOUBLE](-p-o-s-d-o-u-b-l-e.html)(): TerminalNode |
| [removeLastChild](index.html#-2099160366%2FFunctions%2F-134779887) | [jvm]<br>open fun [removeLastChild](index.html#-2099160366%2FFunctions%2F-134779887)() |
| [setAltNumber](index.html#-2115960002%2FFunctions%2F-134779887) | [jvm]<br>open fun [setAltNumber](index.html#-2115960002%2FFunctions%2F-134779887)(altNumber: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [setParent](index.html#1546570001%2FFunctions%2F-134779887) | [jvm]<br>open fun [setParent](index.html#1546570001%2FFunctions%2F-134779887)(parent: RuleContext) |
| [toInfoString](index.html#328935484%2FFunctions%2F-134779887) | [jvm]<br>open fun [toInfoString](index.html#328935484%2FFunctions%2F-134779887)(recognizer: Parser): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [toString](index.html#549784249%2FFunctions%2F-134779887) | [jvm]<br>open fun [toString](index.html#549784249%2FFunctions%2F-134779887)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [toStringTree](index.html#1780528237%2FFunctions%2F-134779887) | [jvm]<br>open fun [toStringTree](index.html#1780528237%2FFunctions%2F-134779887)(recog: Parser): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


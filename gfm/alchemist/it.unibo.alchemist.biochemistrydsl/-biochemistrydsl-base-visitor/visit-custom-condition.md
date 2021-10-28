//[alchemist](../../../index.md)/[it.unibo.alchemist.biochemistrydsl](../index.md)/[BiochemistrydslBaseVisitor](index.md)/[visitCustomCondition](visit-custom-condition.md)

# visitCustomCondition

[jvm]\
open fun [visitCustomCondition](visit-custom-condition.md)(ctx: [BiochemistrydslParser.CustomConditionContext](../-biochemistrydsl-parser/-custom-condition-context/index.md)): [T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.md)

Visit a parse tree produced by BiochemistrydslParser#customCondition. 

The default implementation returns the result of calling [visitChildren](index.md#668592954%2FFunctions%2F-267951372) on {@code ctx}.

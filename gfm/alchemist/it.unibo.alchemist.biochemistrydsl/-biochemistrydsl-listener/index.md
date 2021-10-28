//[alchemist](../../../index.md)/[it.unibo.alchemist.biochemistrydsl](../index.md)/[BiochemistrydslListener](index.md)

# BiochemistrydslListener

[jvm]\
interface [BiochemistrydslListener](index.md) : ParseTreeListener

This interface defines a complete listener for a parse tree produced by [BiochemistrydslParser](../-biochemistrydsl-parser/index.md).

## Functions

| Name | Summary |
|---|---|
| [enterArg](enter-arg.md) | [jvm]<br>abstract fun [enterArg](enter-arg.md)(ctx: [BiochemistrydslParser.ArgContext](../-biochemistrydsl-parser/-arg-context/index.md))<br>Enter a parse tree produced by [arg](../-biochemistrydsl-parser/arg.md). |
| [enterArgList](enter-arg-list.md) | [jvm]<br>abstract fun [enterArgList](enter-arg-list.md)(ctx: [BiochemistrydslParser.ArgListContext](../-biochemistrydsl-parser/-arg-list-context/index.md))<br>Enter a parse tree produced by [argList](../-biochemistrydsl-parser/arg-list.md). |
| [enterBiochemicalReaction](enter-biochemical-reaction.md) | [jvm]<br>abstract fun [enterBiochemicalReaction](enter-biochemical-reaction.md)(ctx: [BiochemistrydslParser.BiochemicalReactionContext](../-biochemistrydsl-parser/-biochemical-reaction-context/index.md))<br>Enter a parse tree produced by [biochemicalReaction](../-biochemistrydsl-parser/biochemical-reaction.md). |
| [enterBiochemicalReactionLeft](enter-biochemical-reaction-left.md) | [jvm]<br>abstract fun [enterBiochemicalReactionLeft](enter-biochemical-reaction-left.md)(ctx: [BiochemistrydslParser.BiochemicalReactionLeftContext](../-biochemistrydsl-parser/-biochemical-reaction-left-context/index.md))<br>Enter a parse tree produced by [biochemicalReactionLeft](../-biochemistrydsl-parser/biochemical-reaction-left.md). |
| [enterBiochemicalReactionLeftContext](enter-biochemical-reaction-left-context.md) | [jvm]<br>abstract fun [enterBiochemicalReactionLeftContext](enter-biochemical-reaction-left-context.md)(ctx: [BiochemistrydslParser.BiochemicalReactionLeftContextContext](../-biochemistrydsl-parser/-biochemical-reaction-left-context-context/index.md))<br>Enter a parse tree produced by [biochemicalReactionLeftContext](../-biochemistrydsl-parser/biochemical-reaction-left-context.md). |
| [enterBiochemicalReactionLeftInCellContext](enter-biochemical-reaction-left-in-cell-context.md) | [jvm]<br>abstract fun [enterBiochemicalReactionLeftInCellContext](enter-biochemical-reaction-left-in-cell-context.md)(ctx: [BiochemistrydslParser.BiochemicalReactionLeftInCellContextContext](../-biochemistrydsl-parser/-biochemical-reaction-left-in-cell-context-context/index.md))<br>Enter a parse tree produced by [biochemicalReactionLeftInCellContext](../-biochemistrydsl-parser/biochemical-reaction-left-in-cell-context.md). |
| [enterBiochemicalReactionLeftInEnvContext](enter-biochemical-reaction-left-in-env-context.md) | [jvm]<br>abstract fun [enterBiochemicalReactionLeftInEnvContext](enter-biochemical-reaction-left-in-env-context.md)(ctx: [BiochemistrydslParser.BiochemicalReactionLeftInEnvContextContext](../-biochemistrydsl-parser/-biochemical-reaction-left-in-env-context-context/index.md))<br>Enter a parse tree produced by [biochemicalReactionLeftInEnvContext](../-biochemistrydsl-parser/biochemical-reaction-left-in-env-context.md). |
| [enterBiochemicalReactionLeftInNeighborContext](enter-biochemical-reaction-left-in-neighbor-context.md) | [jvm]<br>abstract fun [enterBiochemicalReactionLeftInNeighborContext](enter-biochemical-reaction-left-in-neighbor-context.md)(ctx: [BiochemistrydslParser.BiochemicalReactionLeftInNeighborContextContext](../-biochemistrydsl-parser/-biochemical-reaction-left-in-neighbor-context-context/index.md))<br>Enter a parse tree produced by [biochemicalReactionLeftInNeighborContext](../-biochemistrydsl-parser/biochemical-reaction-left-in-neighbor-context.md). |
| [enterBiochemicalReactionRight](enter-biochemical-reaction-right.md) | [jvm]<br>abstract fun [enterBiochemicalReactionRight](enter-biochemical-reaction-right.md)(ctx: [BiochemistrydslParser.BiochemicalReactionRightContext](../-biochemistrydsl-parser/-biochemical-reaction-right-context/index.md))<br>Enter a parse tree produced by [biochemicalReactionRight](../-biochemistrydsl-parser/biochemical-reaction-right.md). |
| [enterBiochemicalReactionRightContext](enter-biochemical-reaction-right-context.md) | [jvm]<br>abstract fun [enterBiochemicalReactionRightContext](enter-biochemical-reaction-right-context.md)(ctx: [BiochemistrydslParser.BiochemicalReactionRightContextContext](../-biochemistrydsl-parser/-biochemical-reaction-right-context-context/index.md))<br>Enter a parse tree produced by [biochemicalReactionRightContext](../-biochemistrydsl-parser/biochemical-reaction-right-context.md). |
| [enterBiochemicalReactionRightElem](enter-biochemical-reaction-right-elem.md) | [jvm]<br>abstract fun [enterBiochemicalReactionRightElem](enter-biochemical-reaction-right-elem.md)(ctx: [BiochemistrydslParser.BiochemicalReactionRightElemContext](../-biochemistrydsl-parser/-biochemical-reaction-right-elem-context/index.md))<br>Enter a parse tree produced by [biochemicalReactionRightElem](../-biochemistrydsl-parser/biochemical-reaction-right-elem.md). |
| [enterBiochemicalReactionRightInCellContext](enter-biochemical-reaction-right-in-cell-context.md) | [jvm]<br>abstract fun [enterBiochemicalReactionRightInCellContext](enter-biochemical-reaction-right-in-cell-context.md)(ctx: [BiochemistrydslParser.BiochemicalReactionRightInCellContextContext](../-biochemistrydsl-parser/-biochemical-reaction-right-in-cell-context-context/index.md))<br>Enter a parse tree produced by [biochemicalReactionRightInCellContext](../-biochemistrydsl-parser/biochemical-reaction-right-in-cell-context.md). |
| [enterBiochemicalReactionRightInEnvContext](enter-biochemical-reaction-right-in-env-context.md) | [jvm]<br>abstract fun [enterBiochemicalReactionRightInEnvContext](enter-biochemical-reaction-right-in-env-context.md)(ctx: [BiochemistrydslParser.BiochemicalReactionRightInEnvContextContext](../-biochemistrydsl-parser/-biochemical-reaction-right-in-env-context-context/index.md))<br>Enter a parse tree produced by [biochemicalReactionRightInEnvContext](../-biochemistrydsl-parser/biochemical-reaction-right-in-env-context.md). |
| [enterBiochemicalReactionRightInNeighborContext](enter-biochemical-reaction-right-in-neighbor-context.md) | [jvm]<br>abstract fun [enterBiochemicalReactionRightInNeighborContext](enter-biochemical-reaction-right-in-neighbor-context.md)(ctx: [BiochemistrydslParser.BiochemicalReactionRightInNeighborContextContext](../-biochemistrydsl-parser/-biochemical-reaction-right-in-neighbor-context-context/index.md))<br>Enter a parse tree produced by [biochemicalReactionRightInNeighborContext](../-biochemistrydsl-parser/biochemical-reaction-right-in-neighbor-context.md). |
| [enterBiomolecule](enter-biomolecule.md) | [jvm]<br>abstract fun [enterBiomolecule](enter-biomolecule.md)(ctx: [BiochemistrydslParser.BiomoleculeContext](../-biochemistrydsl-parser/-biomolecule-context/index.md))<br>Enter a parse tree produced by [biomolecule](../-biochemistrydsl-parser/biomolecule.md). |
| [enterConcentration](enter-concentration.md) | [jvm]<br>abstract fun [enterConcentration](enter-concentration.md)(ctx: [BiochemistrydslParser.ConcentrationContext](../-biochemistrydsl-parser/-concentration-context/index.md))<br>Enter a parse tree produced by [concentration](../-biochemistrydsl-parser/concentration.md). |
| [enterCreateJunction](enter-create-junction.md) | [jvm]<br>abstract fun [enterCreateJunction](enter-create-junction.md)(ctx: [BiochemistrydslParser.CreateJunctionContext](../-biochemistrydsl-parser/-create-junction-context/index.md))<br>Enter a parse tree produced by [createJunction](../-biochemistrydsl-parser/create-junction.md). |
| [enterCreateJunctionJunction](enter-create-junction-junction.md) | [jvm]<br>abstract fun [enterCreateJunctionJunction](enter-create-junction-junction.md)(ctx: [BiochemistrydslParser.CreateJunctionJunctionContext](../-biochemistrydsl-parser/-create-junction-junction-context/index.md))<br>Enter a parse tree produced by [createJunctionJunction](../-biochemistrydsl-parser/create-junction-junction.md). |
| [enterCreateJunctionLeft](enter-create-junction-left.md) | [jvm]<br>abstract fun [enterCreateJunctionLeft](enter-create-junction-left.md)(ctx: [BiochemistrydslParser.CreateJunctionLeftContext](../-biochemistrydsl-parser/-create-junction-left-context/index.md))<br>Enter a parse tree produced by [createJunctionLeft](../-biochemistrydsl-parser/create-junction-left.md). |
| [enterCreateJunctionRight](enter-create-junction-right.md) | [jvm]<br>abstract fun [enterCreateJunctionRight](enter-create-junction-right.md)(ctx: [BiochemistrydslParser.CreateJunctionRightContext](../-biochemistrydsl-parser/-create-junction-right-context/index.md))<br>Enter a parse tree produced by [createJunctionRight](../-biochemistrydsl-parser/create-junction-right.md). |
| [enterCustomCondition](enter-custom-condition.md) | [jvm]<br>abstract fun [enterCustomCondition](enter-custom-condition.md)(ctx: [BiochemistrydslParser.CustomConditionContext](../-biochemistrydsl-parser/-custom-condition-context/index.md))<br>Enter a parse tree produced by [customCondition](../-biochemistrydsl-parser/custom-condition.md). |
| [enterCustomConditions](enter-custom-conditions.md) | [jvm]<br>abstract fun [enterCustomConditions](enter-custom-conditions.md)(ctx: [BiochemistrydslParser.CustomConditionsContext](../-biochemistrydsl-parser/-custom-conditions-context/index.md))<br>Enter a parse tree produced by [customConditions](../-biochemistrydsl-parser/custom-conditions.md). |
| [enterCustomReactionType](enter-custom-reaction-type.md) | [jvm]<br>abstract fun [enterCustomReactionType](enter-custom-reaction-type.md)(ctx: [BiochemistrydslParser.CustomReactionTypeContext](../-biochemistrydsl-parser/-custom-reaction-type-context/index.md))<br>Enter a parse tree produced by [customReactionType](../-biochemistrydsl-parser/custom-reaction-type.md). |
| [enterDecimal](enter-decimal.md) | [jvm]<br>abstract fun [enterDecimal](enter-decimal.md)(ctx: [BiochemistrydslParser.DecimalContext](../-biochemistrydsl-parser/-decimal-context/index.md))<br>Enter a parse tree produced by [decimal](../-biochemistrydsl-parser/decimal.md). |
| [enterEveryRule](index.md#592815717%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [enterEveryRule](index.md#592815717%2FFunctions%2F-267951372)(p: ParserRuleContext) |
| [enterJavaClass](enter-java-class.md) | [jvm]<br>abstract fun [enterJavaClass](enter-java-class.md)(ctx: [BiochemistrydslParser.JavaClassContext](../-biochemistrydsl-parser/-java-class-context/index.md))<br>Enter a parse tree produced by [javaClass](../-biochemistrydsl-parser/java-class.md). |
| [enterJavaConstructor](enter-java-constructor.md) | [jvm]<br>abstract fun [enterJavaConstructor](enter-java-constructor.md)(ctx: [BiochemistrydslParser.JavaConstructorContext](../-biochemistrydsl-parser/-java-constructor-context/index.md))<br>Enter a parse tree produced by [javaConstructor](../-biochemistrydsl-parser/java-constructor.md). |
| [enterJunction](enter-junction.md) | [jvm]<br>abstract fun [enterJunction](enter-junction.md)(ctx: [BiochemistrydslParser.JunctionContext](../-biochemistrydsl-parser/-junction-context/index.md))<br>Enter a parse tree produced by [junction](../-biochemistrydsl-parser/junction.md). |
| [enterJunctionLeft](enter-junction-left.md) | [jvm]<br>abstract fun [enterJunctionLeft](enter-junction-left.md)(ctx: [BiochemistrydslParser.JunctionLeftContext](../-biochemistrydsl-parser/-junction-left-context/index.md))<br>Enter a parse tree produced by [junctionLeft](../-biochemistrydsl-parser/junction-left.md). |
| [enterJunctionReaction](enter-junction-reaction.md) | [jvm]<br>abstract fun [enterJunctionReaction](enter-junction-reaction.md)(ctx: [BiochemistrydslParser.JunctionReactionContext](../-biochemistrydsl-parser/-junction-reaction-context/index.md))<br>Enter a parse tree produced by [junctionReaction](../-biochemistrydsl-parser/junction-reaction.md). |
| [enterJunctionReactionJunction](enter-junction-reaction-junction.md) | [jvm]<br>abstract fun [enterJunctionReactionJunction](enter-junction-reaction-junction.md)(ctx: [BiochemistrydslParser.JunctionReactionJunctionContext](../-biochemistrydsl-parser/-junction-reaction-junction-context/index.md))<br>Enter a parse tree produced by [junctionReactionJunction](../-biochemistrydsl-parser/junction-reaction-junction.md). |
| [enterJunctionReactionJunctionCondition](enter-junction-reaction-junction-condition.md) | [jvm]<br>abstract fun [enterJunctionReactionJunctionCondition](enter-junction-reaction-junction-condition.md)(ctx: [BiochemistrydslParser.JunctionReactionJunctionConditionContext](../-biochemistrydsl-parser/-junction-reaction-junction-condition-context/index.md))<br>Enter a parse tree produced by [junctionReactionJunctionCondition](../-biochemistrydsl-parser/junction-reaction-junction-condition.md). |
| [enterJunctionReactionLeft](enter-junction-reaction-left.md) | [jvm]<br>abstract fun [enterJunctionReactionLeft](enter-junction-reaction-left.md)(ctx: [BiochemistrydslParser.JunctionReactionLeftContext](../-biochemistrydsl-parser/-junction-reaction-left-context/index.md))<br>Enter a parse tree produced by [junctionReactionLeft](../-biochemistrydsl-parser/junction-reaction-left.md). |
| [enterJunctionReactionRight](enter-junction-reaction-right.md) | [jvm]<br>abstract fun [enterJunctionReactionRight](enter-junction-reaction-right.md)(ctx: [BiochemistrydslParser.JunctionReactionRightContext](../-biochemistrydsl-parser/-junction-reaction-right-context/index.md))<br>Enter a parse tree produced by [junctionReactionRight](../-biochemistrydsl-parser/junction-reaction-right.md). |
| [enterJunctionRight](enter-junction-right.md) | [jvm]<br>abstract fun [enterJunctionRight](enter-junction-right.md)(ctx: [BiochemistrydslParser.JunctionRightContext](../-biochemistrydsl-parser/-junction-right-context/index.md))<br>Enter a parse tree produced by [junctionRight](../-biochemistrydsl-parser/junction-right.md). |
| [enterReaction](enter-reaction.md) | [jvm]<br>abstract fun [enterReaction](enter-reaction.md)(ctx: [BiochemistrydslParser.ReactionContext](../-biochemistrydsl-parser/-reaction-context/index.md))<br>Enter a parse tree produced by [reaction](../-biochemistrydsl-parser/reaction.md). |
| [exitArg](exit-arg.md) | [jvm]<br>abstract fun [exitArg](exit-arg.md)(ctx: [BiochemistrydslParser.ArgContext](../-biochemistrydsl-parser/-arg-context/index.md))<br>Exit a parse tree produced by [arg](../-biochemistrydsl-parser/arg.md). |
| [exitArgList](exit-arg-list.md) | [jvm]<br>abstract fun [exitArgList](exit-arg-list.md)(ctx: [BiochemistrydslParser.ArgListContext](../-biochemistrydsl-parser/-arg-list-context/index.md))<br>Exit a parse tree produced by [argList](../-biochemistrydsl-parser/arg-list.md). |
| [exitBiochemicalReaction](exit-biochemical-reaction.md) | [jvm]<br>abstract fun [exitBiochemicalReaction](exit-biochemical-reaction.md)(ctx: [BiochemistrydslParser.BiochemicalReactionContext](../-biochemistrydsl-parser/-biochemical-reaction-context/index.md))<br>Exit a parse tree produced by [biochemicalReaction](../-biochemistrydsl-parser/biochemical-reaction.md). |
| [exitBiochemicalReactionLeft](exit-biochemical-reaction-left.md) | [jvm]<br>abstract fun [exitBiochemicalReactionLeft](exit-biochemical-reaction-left.md)(ctx: [BiochemistrydslParser.BiochemicalReactionLeftContext](../-biochemistrydsl-parser/-biochemical-reaction-left-context/index.md))<br>Exit a parse tree produced by [biochemicalReactionLeft](../-biochemistrydsl-parser/biochemical-reaction-left.md). |
| [exitBiochemicalReactionLeftContext](exit-biochemical-reaction-left-context.md) | [jvm]<br>abstract fun [exitBiochemicalReactionLeftContext](exit-biochemical-reaction-left-context.md)(ctx: [BiochemistrydslParser.BiochemicalReactionLeftContextContext](../-biochemistrydsl-parser/-biochemical-reaction-left-context-context/index.md))<br>Exit a parse tree produced by [biochemicalReactionLeftContext](../-biochemistrydsl-parser/biochemical-reaction-left-context.md). |
| [exitBiochemicalReactionLeftInCellContext](exit-biochemical-reaction-left-in-cell-context.md) | [jvm]<br>abstract fun [exitBiochemicalReactionLeftInCellContext](exit-biochemical-reaction-left-in-cell-context.md)(ctx: [BiochemistrydslParser.BiochemicalReactionLeftInCellContextContext](../-biochemistrydsl-parser/-biochemical-reaction-left-in-cell-context-context/index.md))<br>Exit a parse tree produced by [biochemicalReactionLeftInCellContext](../-biochemistrydsl-parser/biochemical-reaction-left-in-cell-context.md). |
| [exitBiochemicalReactionLeftInEnvContext](exit-biochemical-reaction-left-in-env-context.md) | [jvm]<br>abstract fun [exitBiochemicalReactionLeftInEnvContext](exit-biochemical-reaction-left-in-env-context.md)(ctx: [BiochemistrydslParser.BiochemicalReactionLeftInEnvContextContext](../-biochemistrydsl-parser/-biochemical-reaction-left-in-env-context-context/index.md))<br>Exit a parse tree produced by [biochemicalReactionLeftInEnvContext](../-biochemistrydsl-parser/biochemical-reaction-left-in-env-context.md). |
| [exitBiochemicalReactionLeftInNeighborContext](exit-biochemical-reaction-left-in-neighbor-context.md) | [jvm]<br>abstract fun [exitBiochemicalReactionLeftInNeighborContext](exit-biochemical-reaction-left-in-neighbor-context.md)(ctx: [BiochemistrydslParser.BiochemicalReactionLeftInNeighborContextContext](../-biochemistrydsl-parser/-biochemical-reaction-left-in-neighbor-context-context/index.md))<br>Exit a parse tree produced by [biochemicalReactionLeftInNeighborContext](../-biochemistrydsl-parser/biochemical-reaction-left-in-neighbor-context.md). |
| [exitBiochemicalReactionRight](exit-biochemical-reaction-right.md) | [jvm]<br>abstract fun [exitBiochemicalReactionRight](exit-biochemical-reaction-right.md)(ctx: [BiochemistrydslParser.BiochemicalReactionRightContext](../-biochemistrydsl-parser/-biochemical-reaction-right-context/index.md))<br>Exit a parse tree produced by [biochemicalReactionRight](../-biochemistrydsl-parser/biochemical-reaction-right.md). |
| [exitBiochemicalReactionRightContext](exit-biochemical-reaction-right-context.md) | [jvm]<br>abstract fun [exitBiochemicalReactionRightContext](exit-biochemical-reaction-right-context.md)(ctx: [BiochemistrydslParser.BiochemicalReactionRightContextContext](../-biochemistrydsl-parser/-biochemical-reaction-right-context-context/index.md))<br>Exit a parse tree produced by [biochemicalReactionRightContext](../-biochemistrydsl-parser/biochemical-reaction-right-context.md). |
| [exitBiochemicalReactionRightElem](exit-biochemical-reaction-right-elem.md) | [jvm]<br>abstract fun [exitBiochemicalReactionRightElem](exit-biochemical-reaction-right-elem.md)(ctx: [BiochemistrydslParser.BiochemicalReactionRightElemContext](../-biochemistrydsl-parser/-biochemical-reaction-right-elem-context/index.md))<br>Exit a parse tree produced by [biochemicalReactionRightElem](../-biochemistrydsl-parser/biochemical-reaction-right-elem.md). |
| [exitBiochemicalReactionRightInCellContext](exit-biochemical-reaction-right-in-cell-context.md) | [jvm]<br>abstract fun [exitBiochemicalReactionRightInCellContext](exit-biochemical-reaction-right-in-cell-context.md)(ctx: [BiochemistrydslParser.BiochemicalReactionRightInCellContextContext](../-biochemistrydsl-parser/-biochemical-reaction-right-in-cell-context-context/index.md))<br>Exit a parse tree produced by [biochemicalReactionRightInCellContext](../-biochemistrydsl-parser/biochemical-reaction-right-in-cell-context.md). |
| [exitBiochemicalReactionRightInEnvContext](exit-biochemical-reaction-right-in-env-context.md) | [jvm]<br>abstract fun [exitBiochemicalReactionRightInEnvContext](exit-biochemical-reaction-right-in-env-context.md)(ctx: [BiochemistrydslParser.BiochemicalReactionRightInEnvContextContext](../-biochemistrydsl-parser/-biochemical-reaction-right-in-env-context-context/index.md))<br>Exit a parse tree produced by [biochemicalReactionRightInEnvContext](../-biochemistrydsl-parser/biochemical-reaction-right-in-env-context.md). |
| [exitBiochemicalReactionRightInNeighborContext](exit-biochemical-reaction-right-in-neighbor-context.md) | [jvm]<br>abstract fun [exitBiochemicalReactionRightInNeighborContext](exit-biochemical-reaction-right-in-neighbor-context.md)(ctx: [BiochemistrydslParser.BiochemicalReactionRightInNeighborContextContext](../-biochemistrydsl-parser/-biochemical-reaction-right-in-neighbor-context-context/index.md))<br>Exit a parse tree produced by [biochemicalReactionRightInNeighborContext](../-biochemistrydsl-parser/biochemical-reaction-right-in-neighbor-context.md). |
| [exitBiomolecule](exit-biomolecule.md) | [jvm]<br>abstract fun [exitBiomolecule](exit-biomolecule.md)(ctx: [BiochemistrydslParser.BiomoleculeContext](../-biochemistrydsl-parser/-biomolecule-context/index.md))<br>Exit a parse tree produced by [biomolecule](../-biochemistrydsl-parser/biomolecule.md). |
| [exitConcentration](exit-concentration.md) | [jvm]<br>abstract fun [exitConcentration](exit-concentration.md)(ctx: [BiochemistrydslParser.ConcentrationContext](../-biochemistrydsl-parser/-concentration-context/index.md))<br>Exit a parse tree produced by [concentration](../-biochemistrydsl-parser/concentration.md). |
| [exitCreateJunction](exit-create-junction.md) | [jvm]<br>abstract fun [exitCreateJunction](exit-create-junction.md)(ctx: [BiochemistrydslParser.CreateJunctionContext](../-biochemistrydsl-parser/-create-junction-context/index.md))<br>Exit a parse tree produced by [createJunction](../-biochemistrydsl-parser/create-junction.md). |
| [exitCreateJunctionJunction](exit-create-junction-junction.md) | [jvm]<br>abstract fun [exitCreateJunctionJunction](exit-create-junction-junction.md)(ctx: [BiochemistrydslParser.CreateJunctionJunctionContext](../-biochemistrydsl-parser/-create-junction-junction-context/index.md))<br>Exit a parse tree produced by [createJunctionJunction](../-biochemistrydsl-parser/create-junction-junction.md). |
| [exitCreateJunctionLeft](exit-create-junction-left.md) | [jvm]<br>abstract fun [exitCreateJunctionLeft](exit-create-junction-left.md)(ctx: [BiochemistrydslParser.CreateJunctionLeftContext](../-biochemistrydsl-parser/-create-junction-left-context/index.md))<br>Exit a parse tree produced by [createJunctionLeft](../-biochemistrydsl-parser/create-junction-left.md). |
| [exitCreateJunctionRight](exit-create-junction-right.md) | [jvm]<br>abstract fun [exitCreateJunctionRight](exit-create-junction-right.md)(ctx: [BiochemistrydslParser.CreateJunctionRightContext](../-biochemistrydsl-parser/-create-junction-right-context/index.md))<br>Exit a parse tree produced by [createJunctionRight](../-biochemistrydsl-parser/create-junction-right.md). |
| [exitCustomCondition](exit-custom-condition.md) | [jvm]<br>abstract fun [exitCustomCondition](exit-custom-condition.md)(ctx: [BiochemistrydslParser.CustomConditionContext](../-biochemistrydsl-parser/-custom-condition-context/index.md))<br>Exit a parse tree produced by [customCondition](../-biochemistrydsl-parser/custom-condition.md). |
| [exitCustomConditions](exit-custom-conditions.md) | [jvm]<br>abstract fun [exitCustomConditions](exit-custom-conditions.md)(ctx: [BiochemistrydslParser.CustomConditionsContext](../-biochemistrydsl-parser/-custom-conditions-context/index.md))<br>Exit a parse tree produced by [customConditions](../-biochemistrydsl-parser/custom-conditions.md). |
| [exitCustomReactionType](exit-custom-reaction-type.md) | [jvm]<br>abstract fun [exitCustomReactionType](exit-custom-reaction-type.md)(ctx: [BiochemistrydslParser.CustomReactionTypeContext](../-biochemistrydsl-parser/-custom-reaction-type-context/index.md))<br>Exit a parse tree produced by [customReactionType](../-biochemistrydsl-parser/custom-reaction-type.md). |
| [exitDecimal](exit-decimal.md) | [jvm]<br>abstract fun [exitDecimal](exit-decimal.md)(ctx: [BiochemistrydslParser.DecimalContext](../-biochemistrydsl-parser/-decimal-context/index.md))<br>Exit a parse tree produced by [decimal](../-biochemistrydsl-parser/decimal.md). |
| [exitEveryRule](index.md#327005035%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [exitEveryRule](index.md#327005035%2FFunctions%2F-267951372)(p: ParserRuleContext) |
| [exitJavaClass](exit-java-class.md) | [jvm]<br>abstract fun [exitJavaClass](exit-java-class.md)(ctx: [BiochemistrydslParser.JavaClassContext](../-biochemistrydsl-parser/-java-class-context/index.md))<br>Exit a parse tree produced by [javaClass](../-biochemistrydsl-parser/java-class.md). |
| [exitJavaConstructor](exit-java-constructor.md) | [jvm]<br>abstract fun [exitJavaConstructor](exit-java-constructor.md)(ctx: [BiochemistrydslParser.JavaConstructorContext](../-biochemistrydsl-parser/-java-constructor-context/index.md))<br>Exit a parse tree produced by [javaConstructor](../-biochemistrydsl-parser/java-constructor.md). |
| [exitJunction](exit-junction.md) | [jvm]<br>abstract fun [exitJunction](exit-junction.md)(ctx: [BiochemistrydslParser.JunctionContext](../-biochemistrydsl-parser/-junction-context/index.md))<br>Exit a parse tree produced by [junction](../-biochemistrydsl-parser/junction.md). |
| [exitJunctionLeft](exit-junction-left.md) | [jvm]<br>abstract fun [exitJunctionLeft](exit-junction-left.md)(ctx: [BiochemistrydslParser.JunctionLeftContext](../-biochemistrydsl-parser/-junction-left-context/index.md))<br>Exit a parse tree produced by [junctionLeft](../-biochemistrydsl-parser/junction-left.md). |
| [exitJunctionReaction](exit-junction-reaction.md) | [jvm]<br>abstract fun [exitJunctionReaction](exit-junction-reaction.md)(ctx: [BiochemistrydslParser.JunctionReactionContext](../-biochemistrydsl-parser/-junction-reaction-context/index.md))<br>Exit a parse tree produced by [junctionReaction](../-biochemistrydsl-parser/junction-reaction.md). |
| [exitJunctionReactionJunction](exit-junction-reaction-junction.md) | [jvm]<br>abstract fun [exitJunctionReactionJunction](exit-junction-reaction-junction.md)(ctx: [BiochemistrydslParser.JunctionReactionJunctionContext](../-biochemistrydsl-parser/-junction-reaction-junction-context/index.md))<br>Exit a parse tree produced by [junctionReactionJunction](../-biochemistrydsl-parser/junction-reaction-junction.md). |
| [exitJunctionReactionJunctionCondition](exit-junction-reaction-junction-condition.md) | [jvm]<br>abstract fun [exitJunctionReactionJunctionCondition](exit-junction-reaction-junction-condition.md)(ctx: [BiochemistrydslParser.JunctionReactionJunctionConditionContext](../-biochemistrydsl-parser/-junction-reaction-junction-condition-context/index.md))<br>Exit a parse tree produced by [junctionReactionJunctionCondition](../-biochemistrydsl-parser/junction-reaction-junction-condition.md). |
| [exitJunctionReactionLeft](exit-junction-reaction-left.md) | [jvm]<br>abstract fun [exitJunctionReactionLeft](exit-junction-reaction-left.md)(ctx: [BiochemistrydslParser.JunctionReactionLeftContext](../-biochemistrydsl-parser/-junction-reaction-left-context/index.md))<br>Exit a parse tree produced by [junctionReactionLeft](../-biochemistrydsl-parser/junction-reaction-left.md). |
| [exitJunctionReactionRight](exit-junction-reaction-right.md) | [jvm]<br>abstract fun [exitJunctionReactionRight](exit-junction-reaction-right.md)(ctx: [BiochemistrydslParser.JunctionReactionRightContext](../-biochemistrydsl-parser/-junction-reaction-right-context/index.md))<br>Exit a parse tree produced by [junctionReactionRight](../-biochemistrydsl-parser/junction-reaction-right.md). |
| [exitJunctionRight](exit-junction-right.md) | [jvm]<br>abstract fun [exitJunctionRight](exit-junction-right.md)(ctx: [BiochemistrydslParser.JunctionRightContext](../-biochemistrydsl-parser/-junction-right-context/index.md))<br>Exit a parse tree produced by [junctionRight](../-biochemistrydsl-parser/junction-right.md). |
| [exitReaction](exit-reaction.md) | [jvm]<br>abstract fun [exitReaction](exit-reaction.md)(ctx: [BiochemistrydslParser.ReactionContext](../-biochemistrydsl-parser/-reaction-context/index.md))<br>Exit a parse tree produced by [reaction](../-biochemistrydsl-parser/reaction.md). |
| [visitErrorNode](index.md#-64790961%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [visitErrorNode](index.md#-64790961%2FFunctions%2F-267951372)(p: ErrorNode) |
| [visitTerminal](index.md#891846403%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [visitTerminal](index.md#891846403%2FFunctions%2F-267951372)(p: TerminalNode) |

## Inheritors

| Name |
|---|
| [BiochemistrydslBaseListener](../-biochemistrydsl-base-listener/index.md) |
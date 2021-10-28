//[alchemist](../../../index.md)/[it.unibo.alchemist.expressions.implementations](../index.md)/[Expression](index.md)/[matches](matches.md)

# matches

[jvm]\
open fun [matches](matches.md)(expr: [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.md), matches: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Tries to match this expression with expr. The matching rules are: (i) a variable matches everything; (ii) a constant value matches an identical constant value; (iii) a number matches an identical number or an operator, (iv) operators match everything but constants, (v) comparators match numbers and operators (verifying the values); (vi) expr type can't be comparator; (vii) add and rem operators work only with lists.

#### Return

true if this expression can "match" with expr.

## Parameters

jvm

| | |
|---|---|
| expr | the expression to match |
| map | the matches map |

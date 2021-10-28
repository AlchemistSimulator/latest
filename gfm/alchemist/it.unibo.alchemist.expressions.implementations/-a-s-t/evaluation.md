//[alchemist](../../../index.md)/[it.unibo.alchemist.expressions.implementations](../index.md)/[AST](index.md)/[evaluation](evaluation.md)

# evaluation

[jvm]\
open fun [evaluation](evaluation.md)(matches: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)

This evaluates the expression. If the matches map contains values which are not instanced, and the expression value cannot consequently be computed, 0d is returned.

#### Return

A number representing the value for this expression. If the expression can't be computed, an exception is thrown.

## Parameters

jvm

| | |
|---|---|
| matches | the map that binds each variable with its own value |

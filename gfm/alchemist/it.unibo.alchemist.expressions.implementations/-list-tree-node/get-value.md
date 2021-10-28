//[alchemist](../../../index.md)/[it.unibo.alchemist.expressions.implementations](../index.md)/[ListTreeNode](index.md)/[getValue](get-value.md)

# getValue

[jvm]\
open fun [getValue](get-value.md)(mp: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [Set](https://docs.oracle.com/javase/8/docs/api/java/util/Set.html)<[ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>

#### Return

the value of the Node. (Double if it's a Num or a Var of type Num, String if it's a Const or a Var of type Const) the method return null if there are some variable not yet allocated in the expression.

## Parameters

jvm

| | |
|---|---|
| mp | the matches map. If it is not available or not required (e.g. for evaluating a number or a const), then null values can be used |

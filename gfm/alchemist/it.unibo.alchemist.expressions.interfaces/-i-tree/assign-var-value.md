//[alchemist](../../../index.md)/[it.unibo.alchemist.expressions.interfaces](../index.md)/[ITree](index.md)/[assignVarValue](assign-var-value.md)

# assignVarValue

[jvm]\
abstract fun [assignVarValue](assign-var-value.md)(matches: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [ITree](index.md)

This method substitutes variables present in matches map with their values. It must involve only node of Typ=Var. The method must also recognize the values type stored in the map (they can be Const or Num).

#### Return

a new ITree containing the instantiated variable

## Parameters

jvm

| | |
|---|---|
| matches | the map with variable values already assigned. |

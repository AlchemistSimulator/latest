---
title: ILsaMolecule
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[ILsaMolecule](index.html)



# ILsaMolecule



[jvm]\
interface [ILsaMolecule](index.html) : [Molecule](../-molecule/index.html), [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)<[IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)> , [Comparable](https://docs.oracle.com/javase/8/docs/api/java/lang/Comparable.html)<[ILsaMolecule](index.html)>



## Functions


| Name | Summary |
|---|---|
| [allocateVar](allocate-var.html) | [jvm]<br>abstract fun [allocateVar](allocate-var.html)(matches: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)><br>the map with the variable / value bindings |
| [argsNumber](args-number.html) | [jvm]<br>abstract fun [argsNumber](args-number.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the arguments number of the LSA structure. |
| [compareTo](../-g-p-s-point/index.html#-1554281679%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [compareTo](../-g-p-s-point/index.html#-1554281679%2FFunctions%2F-134779887)(p: [T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [dependsOn](../-dependency/depends-on.html) | [jvm]<br>open fun [dependsOn](../-dependency/depends-on.html)(dependency: [Dependency](../-dependency/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [equals](equals.html) | [jvm]<br>abstract fun [equals](equals.html)(mol: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if the molecule arguments match with mol arguments. |
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [generalize](generalize.html) | [jvm]<br>abstract fun [generalize](generalize.html)(): [ILsaMolecule](index.html)<br>a new [ILsaMolecule](index.html) produced by replacing all non-atomic and non-numeric values with variables. |
| [getArg](get-arg.html) | [jvm]<br>abstract fun [getArg](get-arg.html)(i: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)<br>: position of the argument to get |
| [getName](../-molecule/get-name.html) | [jvm]<br>abstract fun [getName](../-molecule/get-name.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [hasDuplicateVariables](has-duplicate-variables.html) | [jvm]<br>abstract fun [hasDuplicateVariables](has-duplicate-variables.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if this variable makes use of variables defined within the molecule itself |
| [isIdenticalTo](is-identical-to.html) | [jvm]<br>abstract fun [isIdenticalTo](is-identical-to.html)(mol: [ILsaMolecule](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>the molecule to compare to |
| [isIstance](is-istance.html) | [jvm]<br>abstract fun [isIstance](is-istance.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if the molecule is an instance (not variable in the argouments). |
| [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.html)> |
| [makesDependent](../-dependency/makes-dependent.html) | [jvm]<br>open fun [makesDependent](../-dependency/makes-dependent.html)(dependency: [Dependency](../-dependency/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [matches](matches.html) | [jvm]<br>abstract fun [matches](matches.html)(mol: [ILsaMolecule](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>the LsaMolecule to try to match with.<br>[jvm]<br>abstract fun [matches](matches.html)(mol: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<out [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)>, duplicateVariables: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>the LsaMolecule to try to match with |
| [moreGenericOf](more-generic-of.html) | [jvm]<br>abstract fun [moreGenericOf](more-generic-of.html)(mol: [ILsaMolecule](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>the molecule to compare to |
| [size](size.html) | [jvm]<br>abstract fun [size](size.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the number of arguments |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-abstract-action/index.html)> |
| [toHashString](to-hash-string.html) | [jvm]<br>abstract fun [toHashString](to-hash-string.html)(): HashString<br>the string representing the molecule, in a faster implementation. |
| [toString](to-string.html) | [jvm]<br>abstract fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>the string representing the molecule. |


## Inheritors


| Name |
|---|
| [LsaMolecule](../../it.unibo.alchemist.model.implementations.molecules/-lsa-molecule/index.html) |


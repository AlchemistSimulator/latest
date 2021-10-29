//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[ILsaMolecule](index.md)

# ILsaMolecule

[jvm]\
interface [ILsaMolecule](index.md) : [Molecule](../-molecule/index.md), [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)<[IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.md)> , [Comparable](https://docs.oracle.com/javase/8/docs/api/java/lang/Comparable.html)<[ILsaMolecule](index.md)>

## Functions

| Name | Summary |
|---|---|
| [allocateVar](allocate-var.md) | [jvm]<br>abstract fun [allocateVar](allocate-var.md)(matches: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.md)><br>the map with the variable / value bindings |
| [argsNumber](args-number.md) | [jvm]<br>abstract fun [argsNumber](args-number.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the arguments number of the LSA structure. |
| [compareTo](../-g-p-s-point/index.md#-1554281679%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [compareTo](../-g-p-s-point/index.md#-1554281679%2FFunctions%2F-267951372)(p: [T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [dependsOn](../-dependency/depends-on.md) | [jvm]<br>open fun [dependsOn](../-dependency/depends-on.md)(dependency: [Dependency](../-dependency/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [equals](equals.md) | [jvm]<br>abstract fun [equals](equals.md)(mol: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if the molecule arguments match with mol arguments. |
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [generalize](generalize.md) | [jvm]<br>abstract fun [generalize](generalize.md)(): [ILsaMolecule](index.md)<br>a new [ILsaMolecule](index.md) produced by replacing all non-atomic and non-numeric values with variables. |
| [getArg](get-arg.md) | [jvm]<br>abstract fun [getArg](get-arg.md)(i: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.md)<br>: position of the argument to get |
| [getName](../-molecule/get-name.md) | [jvm]<br>abstract fun [getName](../-molecule/get-name.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [hasDuplicateVariables](has-duplicate-variables.md) | [jvm]<br>abstract fun [hasDuplicateVariables](has-duplicate-variables.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if this variable makes use of variables defined within the molecule itself |
| [isIdenticalTo](is-identical-to.md) | [jvm]<br>abstract fun [isIdenticalTo](is-identical-to.md)(mol: [ILsaMolecule](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>the molecule to compare to |
| [isIstance](is-istance.md) | [jvm]<br>abstract fun [isIstance](is-istance.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if the molecule is an instance (not variable in the argouments). |
| [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)> |
| [makesDependent](../-dependency/makes-dependent.md) | [jvm]<br>open fun [makesDependent](../-dependency/makes-dependent.md)(dependency: [Dependency](../-dependency/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [matches](matches.md) | [jvm]<br>abstract fun [matches](matches.md)(mol: [ILsaMolecule](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>the LsaMolecule to try to match with.<br>[jvm]<br>abstract fun [matches](matches.md)(mol: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<out [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.md)>, duplicateVariables: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>the LsaMolecule to try to match with |
| [moreGenericOf](more-generic-of.md) | [jvm]<br>abstract fun [moreGenericOf](more-generic-of.md)(mol: [ILsaMolecule](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>the molecule to compare to |
| [size](size.md) | [jvm]<br>abstract fun [size](size.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the number of arguments |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-abstract-condition/index.md)> |
| [toHashString](to-hash-string.md) | [jvm]<br>abstract fun [toHashString](to-hash-string.md)(): HashString<br>the string representing the molecule, in a faster implementation. |
| [toString](to-string.md) | [jvm]<br>abstract fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>the string representing the molecule. |

## Inheritors

| Name |
|---|
| [LsaMolecule](../../it.unibo.alchemist.model.implementations.molecules/-lsa-molecule/index.md) |

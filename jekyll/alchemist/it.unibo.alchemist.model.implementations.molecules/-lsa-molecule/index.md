---
title: LsaMolecule
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.molecules](../index.html)/[LsaMolecule](index.html)



# LsaMolecule



[jvm]\
class [LsaMolecule](index.html) : [SimpleMolecule](../-simple-molecule/index.html), [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)

This class realizes an LsaMolecule, where arguments are of type Expression.



## Constructors


| | |
|---|---|
| [LsaMolecule](-lsa-molecule.html) | [jvm]<br>open fun [LsaMolecule](-lsa-molecule.html)()<br>Empty molecule, no arguments. |
| [LsaMolecule](-lsa-molecule.html) | [jvm]<br>open fun [LsaMolecule](-lsa-molecule.html)(@[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()listArgs: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)>)<br>Builds a new LsaMolecule by interpreting a list of IExpressions. |
| [LsaMolecule](-lsa-molecule.html) | [jvm]<br>open fun [LsaMolecule](-lsa-molecule.html)(m: [LsaMolecule](index.html))<br>Very fast constructor, produces a copy of an LsaMolecule. |
| [LsaMolecule](-lsa-molecule.html) | [jvm]<br>open fun [LsaMolecule](-lsa-molecule.html)(argsString: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Builds a LsaMolecule by parsing the passed String. |
| [LsaMolecule](-lsa-molecule.html) | [jvm]<br>open fun [LsaMolecule](-lsa-molecule.html)(argsString: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), description: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Builds a LsaMolecule by parsing the passed String. |


## Functions


| Name | Summary |
|---|---|
| [allocateVar](allocate-var.html) | [jvm]<br>open fun [allocateVar](allocate-var.html)(matches: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)><br>the map with the variable / value bindings |
| [argsNumber](args-number.html) | [jvm]<br>open fun [argsNumber](args-number.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the arguments number of the LSA structure. |
| [compareTo](compare-to.html) | [jvm]<br>open fun [compareTo](compare-to.html)(o: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [dependsOn](depends-on.html) | [jvm]<br>open fun [dependsOn](depends-on.html)(m: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [equals](equals.html) | [jvm]<br>open fun [equals](equals.html)(o: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](for-each.html) | [jvm]<br>open fun [forEach](for-each.html)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [generalize](generalize.html) | [jvm]<br>open fun [generalize](generalize.html)(): [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)<br>a new [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html) produced by replacing all non-atomic and non-numeric values with variables. |
| [getArg](get-arg.html) | [jvm]<br>open fun [getArg](get-arg.html)(i: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)<br>: position of the argument to get |
| [getName](../-simple-molecule/get-name.html) | [jvm]<br>fun [getName](../-simple-molecule/get-name.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [hasDuplicateVariables](has-duplicate-variables.html) | [jvm]<br>open fun [hasDuplicateVariables](has-duplicate-variables.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if this variable makes use of variables defined within the molecule itself |
| [hashCode](hash-code.html) | [jvm]<br>open fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isIdenticalTo](is-identical-to.html) | [jvm]<br>open fun [isIdenticalTo](is-identical-to.html)(mol: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>the molecule to compare to |
| [isIstance](is-istance.html) | [jvm]<br>open fun [isIstance](is-istance.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if the molecule is an instance (not variable in the argouments). |
| [iterator](iterator.html) | [jvm]<br>open fun [iterator](iterator.html)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)> |
| [makesDependent](../../it.unibo.alchemist.model.interfaces/-dependency/makes-dependent.html) | [jvm]<br>open fun [makesDependent](../../it.unibo.alchemist.model.interfaces/-dependency/makes-dependent.html)(dependency: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [matches](matches.html) | [jvm]<br>open fun [matches](matches.html)(mol: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>the LsaMolecule to try to match with.<br>[jvm]<br>open fun [matches](matches.html)(mol: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<out [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)>, duplicateVariables: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>the LsaMolecule to try to match with |
| [moreGenericOf](more-generic-of.html) | [jvm]<br>open fun [moreGenericOf](more-generic-of.html)(mol: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>the molecule to compare to |
| [size](size.html) | [jvm]<br>open fun [size](size.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the number of arguments |
| [spliterator](spliterator.html) | [jvm]<br>open fun [spliterator](spliterator.html)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.html)> |
| [toHashString](to-hash-string.html) | [jvm]<br>open fun [toHashString](to-hash-string.html)(): HashString<br>the string representing the molecule, in a faster implementation. |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Properties


| Name | Summary |
|---|---|
| [SYN_D](-s-y-n_-d.html) | [jvm]<br>val [SYN_D](-s-y-n_-d.html): HashString<br>Synthetic property representing the distance. |
| [SYN_MOL_ID](-s-y-n_-m-o-l_-i-d.html) | [jvm]<br>val [SYN_MOL_ID](-s-y-n_-m-o-l_-i-d.html): HashString<br>Synthetic property representing an LSA ID. |
| [SYN_NEIGH](-s-y-n_-n-e-i-g-h.html) | [jvm]<br>val [SYN_NEIGH](-s-y-n_-n-e-i-g-h.html): HashString<br>Synthetic property representing the current neighborhood. |
| [SYN_NODE_ID](-s-y-n_-n-o-d-e_-i-d.html) | [jvm]<br>val [SYN_NODE_ID](-s-y-n_-n-o-d-e_-i-d.html): HashString<br>Synthetic property representing the local node id. |
| [SYN_O](-s-y-n_-o.html) | [jvm]<br>val [SYN_O](-s-y-n_-o.html): HashString<br>Synthetic property representing the orientation. |
| [SYN_RAND](-s-y-n_-r-a-n-d.html) | [jvm]<br>val [SYN_RAND](-s-y-n_-r-a-n-d.html): HashString<br>Synthetic property representing a random value. |
| [SYN_ROUTE](-s-y-n_-r-o-u-t-e.html) | [jvm]<br>val [SYN_ROUTE](-s-y-n_-r-o-u-t-e.html): HashString<br>Synthetic property representing the distance. |
| [SYN_SELECTED](-s-y-n_-s-e-l-e-c-t-e-d.html) | [jvm]<br>val [SYN_SELECTED](-s-y-n_-s-e-l-e-c-t-e-d.html): HashString<br>Synthetic property representing the current selected neighbor ("+" conditions on the left). |
| [SYN_T](-s-y-n_-t.html) | [jvm]<br>val [SYN_T](-s-y-n_-t.html): HashString<br>Synthetic property representing the current simulation time. |


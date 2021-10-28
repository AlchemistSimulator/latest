//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.molecules](../index.md)/[LsaMolecule](index.md)

# LsaMolecule

[jvm]\
class [LsaMolecule](index.md) : [SimpleMolecule](../-simple-molecule/index.md), [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)

This class realizes an LsaMolecule, where arguments are of type Expression.

## Constructors

| | |
|---|---|
| [LsaMolecule](-lsa-molecule.md) | [jvm]<br>open fun [LsaMolecule](-lsa-molecule.md)()<br>Empty molecule, no arguments. |
| [LsaMolecule](-lsa-molecule.md) | [jvm]<br>open fun [LsaMolecule](-lsa-molecule.md)(@[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()listArgs: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.md)>)<br>Builds a new LsaMolecule by interpreting a list of IExpressions. |
| [LsaMolecule](-lsa-molecule.md) | [jvm]<br>open fun [LsaMolecule](-lsa-molecule.md)(m: [LsaMolecule](index.md))<br>Very fast constructor, produces a copy of an LsaMolecule. |
| [LsaMolecule](-lsa-molecule.md) | [jvm]<br>open fun [LsaMolecule](-lsa-molecule.md)(argsString: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Builds a LsaMolecule by parsing the passed String. |
| [LsaMolecule](-lsa-molecule.md) | [jvm]<br>open fun [LsaMolecule](-lsa-molecule.md)(argsString: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), description: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Builds a LsaMolecule by parsing the passed String. |

## Functions

| Name | Summary |
|---|---|
| [allocateVar](allocate-var.md) | [jvm]<br>open fun [allocateVar](allocate-var.md)(matches: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<HashString, [ITreeNode](../../it.unibo.alchemist.expressions.interfaces/-i-tree-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.md)><br>the map with the variable / value bindings |
| [argsNumber](args-number.md) | [jvm]<br>open fun [argsNumber](args-number.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the arguments number of the LSA structure. |
| [compareTo](compare-to.md) | [jvm]<br>open fun [compareTo](compare-to.md)(o: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [dependsOn](depends-on.md) | [jvm]<br>open fun [dependsOn](depends-on.md)(m: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [equals](equals.md) | [jvm]<br>open fun [equals](equals.md)(o: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](for-each.md) | [jvm]<br>open fun [forEach](for-each.md)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [generalize](generalize.md) | [jvm]<br>open fun [generalize](generalize.md)(): [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)<br>a new [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md) produced by replacing all non-atomic and non-numeric values with variables. |
| [getArg](get-arg.md) | [jvm]<br>open fun [getArg](get-arg.md)(i: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.md)<br>: position of the argument to get |
| [getName](../-simple-molecule/get-name.md) | [jvm]<br>fun [getName](../-simple-molecule/get-name.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [hasDuplicateVariables](has-duplicate-variables.md) | [jvm]<br>open fun [hasDuplicateVariables](has-duplicate-variables.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if this variable makes use of variables defined within the molecule itself |
| [hashCode](hash-code.md) | [jvm]<br>open fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isIdenticalTo](is-identical-to.md) | [jvm]<br>open fun [isIdenticalTo](is-identical-to.md)(mol: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>the molecule to compare to |
| [isIstance](is-istance.md) | [jvm]<br>open fun [isIstance](is-istance.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if the molecule is an instance (not variable in the argouments). |
| [iterator](iterator.md) | [jvm]<br>open fun [iterator](iterator.md)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.md)> |
| [makesDependent](../../it.unibo.alchemist.model.interfaces/-dependency/makes-dependent.md) | [jvm]<br>open fun [makesDependent](../../it.unibo.alchemist.model.interfaces/-dependency/makes-dependent.md)(dependency: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [matches](matches.md) | [jvm]<br>open fun [matches](matches.md)(mol: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>the LsaMolecule to try to match with.<br>[jvm]<br>open fun [matches](matches.md)(mol: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<out [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.md)>, duplicateVariables: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>the LsaMolecule to try to match with |
| [moreGenericOf](more-generic-of.md) | [jvm]<br>open fun [moreGenericOf](more-generic-of.md)(mol: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>the molecule to compare to |
| [size](size.md) | [jvm]<br>open fun [size](size.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the number of arguments |
| [spliterator](spliterator.md) | [jvm]<br>open fun [spliterator](spliterator.md)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.md)> |
| [toHashString](to-hash-string.md) | [jvm]<br>open fun [toHashString](to-hash-string.md)(): HashString<br>the string representing the molecule, in a faster implementation. |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

## Properties

| Name | Summary |
|---|---|
| [SYN_D](-s-y-n_-d.md) | [jvm]<br>val [SYN_D](-s-y-n_-d.md): HashString<br>Synthetic property representing the distance. |
| [SYN_MOL_ID](-s-y-n_-m-o-l_-i-d.md) | [jvm]<br>val [SYN_MOL_ID](-s-y-n_-m-o-l_-i-d.md): HashString<br>Synthetic property representing an LSA ID. |
| [SYN_NEIGH](-s-y-n_-n-e-i-g-h.md) | [jvm]<br>val [SYN_NEIGH](-s-y-n_-n-e-i-g-h.md): HashString<br>Synthetic property representing the current neighborhood. |
| [SYN_NODE_ID](-s-y-n_-n-o-d-e_-i-d.md) | [jvm]<br>val [SYN_NODE_ID](-s-y-n_-n-o-d-e_-i-d.md): HashString<br>Synthetic property representing the local node id. |
| [SYN_O](-s-y-n_-o.md) | [jvm]<br>val [SYN_O](-s-y-n_-o.md): HashString<br>Synthetic property representing the orientation. |
| [SYN_RAND](-s-y-n_-r-a-n-d.md) | [jvm]<br>val [SYN_RAND](-s-y-n_-r-a-n-d.md): HashString<br>Synthetic property representing a random value. |
| [SYN_ROUTE](-s-y-n_-r-o-u-t-e.md) | [jvm]<br>val [SYN_ROUTE](-s-y-n_-r-o-u-t-e.md): HashString<br>Synthetic property representing the distance. |
| [SYN_SELECTED](-s-y-n_-s-e-l-e-c-t-e-d.md) | [jvm]<br>val [SYN_SELECTED](-s-y-n_-s-e-l-e-c-t-e-d.md): HashString<br>Synthetic property representing the current selected neighbor ("+" conditions on the left). |
| [SYN_T](-s-y-n_-t.md) | [jvm]<br>val [SYN_T](-s-y-n_-t.md): HashString<br>Synthetic property representing the current simulation time. |

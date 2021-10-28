//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.molecules](../index.md)/[LsaMolecule](index.md)/[matches](matches.md)

# matches

[jvm]\
open fun [matches](matches.md)(mol: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

#### Return

true if the two molecules match

## Parameters

jvm

| | |
|---|---|
| mol | the LsaMolecule to try to match with. |

[jvm]\
open fun [matches](matches.md)(mol: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<out [IExpression](../../it.unibo.alchemist.expressions.interfaces/-i-expression/index.md)>, duplicateVariables: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

#### Return

true if the two molecules match

## Parameters

jvm

| | |
|---|---|
| mol | the LsaMolecule to try to match with |
| duplicateVariables | if true, the matching of variables reused within the same tuple is enabled |
